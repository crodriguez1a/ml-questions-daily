## Day 1

Identify the following machine learning task:

This task predicts a numerical value given some input. To solve this task, the learning algorithm is asked to output a function: <span id="katex_day1_0" class="katex-formula"></span>

---

- A) Classification
- B) Regression
- C) Structured output

<input type="text" placeholder="Type your answer" id="day1_choice" name="day1_choice"/>
<button type="submit" id="day1_submit" class="button">Send</button> 
<div id="day1_feedback"></div>

#### Resources
- [https://machinelearningmastery.com/types-of-learning-in-machine-learning/](https://machinelearningmastery.com/types-of-learning-in-machine-learning/)

- [https://www.deeplearningbook.org/contents/ml.html](https://www.deeplearningbook.org/contents/ml.html)

---

## Day 2

Distinguish between these two machine learning algorithms:

|1|2
|-----|-----
| In this task, the algorithm is given a new example <span id="katex_day2_0" class="katex-formula"></span>, but with some entries missing | In this algorithm, the input is given a *corrupted example* <span id="katex_day2_1"></span>. The algorithm should predict a clean example <span id="katex_day2_2"></span>



---

- A) 1 is Denoising, 2 is Imputation
- B) 1 is Synthesis, 2 is Denoising
- C) 1 is Imputation, 2 is Denoising

<input type="text" placeholder="Type your answer" id="day2_choice" name="day2_choice"/>
<button type="submit" id="day2_submit" class="button">Send</button> 
<div id="day2_feedback"></div>

#### Resources
- [https://alain.xyz/blog/machine-learning-denoising](https://alain.xyz/blog/machine-learning-denoising)

- [https://machinelearningmastery.com/statistical-imputation-for-missing-values-in-machine-learning/](https://machinelearningmastery.com/statistical-imputation-for-missing-values-in-machine-learning/)

- [https://www.deeplearningbook.org/contents/ml.html](https://www.deeplearningbook.org/contents/ml.html)

---




<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/katex@0.12.0/dist/katex.min.css" integrity="sha384-AfEj0r4/OFrOo5t7NnNe46zW/tFgW6x/bCJG8FqQCEo3+Aro6EYUG4+cU+KJWu/X" crossorigin="anonymous">
<style>
  .katex-formula {
    padding: 1em;
    display: inline;
  }
  button[type=submit] {
    border-radius: 5px;
  }
  input {
    padding: 5px;
  }
</style>
<script src="https://cdn.jsdelivr.net/npm/katex@0.12.0/dist/katex.min.js" integrity="sha384-g7c+Jr9ZivxKLnZTDUhnkOnsh30B4H0rpLUpJ4jAIKs4fnJI+sEnkvrMWph2EDg4" crossorigin="anonymous"></script>

<script>
  const selectAnswer = (answer, submit_id, choice_id, feedback_id) => {
    const feedback = document.getElementById(feedback_id)
    const choice = document.getElementById(choice_id);
    console.log(submit_id, choice.value)
    if (choice.value.toLowerCase() == answer) {
      feedback.innerHTML = "Correct!"
    } else {
      feedback.innerHTML = "Not quite."
    }
  }

  const days = [
    [1,"b", [String.raw`f : \R^n \to \R`]],
    [2,"c", [String.raw`x \in \R^n`, String.raw`\hat{x} \in \R^n`, String.raw`x`]]
  ]
  for (let i in  days) {
    [id, ans, formulas] =  days[i]
    let fn = function(id, ans, forumulas) {
       elem = document.getElementById("day" + id + "_submit")
       elem.addEventListener(("click"), () => {
         selectAnswer(ans, "day" + id + "_submit", "day" + id + "_choice", "day" + id + "_feedback")
       });
    
      for (fid in formulas) {
        katex.render(formulas[fid], document.getElementById("katex_day" + id + "_" + fid), {
          throwOnError: false
        });
      }
    }
    fn(id, ans, formulas)
  }
</script>

