## Day 1

Identify the following machine learning task:

This task predicts a numerical value given some input. To solve this task, the learning algorithm is asked to output a function:

<div id="katex_day1" class="katex-formula"></div>

---

- A) Classification
- B) Regression
- C) Structured output

<input type="text" placeholder="Type your answer" id="day1_choice" name="day1_choice"/>
<button type="submit" id="day1_submit" class="button">Send</button> 
<div id="day1_feedback"></div>

- [https://machinelearningmastery.com/types-of-learning-in-machine-learning/](https://machinelearningmastery.com/types-of-learning-in-machine-learning/)

- [https://www.deeplearningbook.org/contents/ml.html](https://www.deeplearningbook.org/contents/ml.html)

---






<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/katex@0.12.0/dist/katex.min.css" integrity="sha384-AfEj0r4/OFrOo5t7NnNe46zW/tFgW6x/bCJG8FqQCEo3+Aro6EYUG4+cU+KJWu/X" crossorigin="anonymous">
<style>
  .katex-formula {
    padding: 1em;
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
    if (choice.value.toLowerCase() == answer) {
      feedback.innerHTML = "Correct!"
    } else {
      feedback.innerHTML = "Not quite."
    }
  }

  const days = [
    [1,"b", String.raw`f : \R^n \to \R`],
  ]
  for (let i in  days) {
    [id, ans, formula] =  days[i]
    document.getElementById("day" + id + "_submit").addEventListener(("click"), () => {
      selectAnswer(ans, "day" + id + "_submit", "day" + id + "_choice", "day" + id + "_feedback")
    });
    
    katex.render(formula, document.getElementById("katex_day" + id), {
      throwOnError: false
    });
  }
</script>

