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

## Day 3

Which of the following is **not** a machine learning technique:

- A) Supervised Learning
- B) Unsupervised Learning
- C) Semi-supervised Learning
- D) Reinforcement Learning
- E) Hyper Learning
- F) Representation Learning

<input type="text" placeholder="Type your answer" id="day3_choice" name="day3_choice"/>
<button type="submit" id="day3_submit" class="button">Send</button> 
<div id="day3_feedback"></div>

#### Resources
- [https://machinelearningmastery.com/a-tour-of-machine-learning-algorithms/](https://machinelearningmastery.com/a-tour-of-machine-learning-algorithms/)

- [https://www.deeplearningbook.org/contents/ml.html](https://www.deeplearningbook.org/contents/ml.html)

---

## Day 4

The ability for a machine learning model to perform well on previously unobserved inputs is called:

- A) Capacity
- B) Generalization
- C) Overfitting

<input type="text" placeholder="Type your answer" id="day4_choice" name="day4_choice"/>
<button type="submit" id="day4_submit" class="button">Send</button> 
<div id="day4_feedback"></div>

#### Resources
- [https://medium.com/@qempsil0914/courseras-machine-learning-notes-week3-overfitting-and-regularization-partii-3e3f3f36a287](https://medium.com/@qempsil0914/courseras-machine-learning-notes-week3-overfitting-and-regularization-partii-3e3f3f36a287)

- [https://www.deeplearningbook.org/contents/ml.html](https://www.deeplearningbook.org/contents/ml.html)

---

## Day 5

Define **Regularization**

- A) Any modification we make to a learning algorithm that is intended to reduce its generalization error but not its training error
- B) A technique used to reduce the errors by fitting the function appropriately on the given training set and avoid overfitting
- C) A technique used for tuning the function by adding an additional penalty term in the error function
- D) All of the above

<input type="text" placeholder="Type your answer" id="day5_choice" name="day5_choice"/>
<button type="submit" id="day5_submit" class="button">Send</button> 
<div id="day5_feedback"></div>

#### Resources
- [https://towardsdatascience.com/regularization-an-important-concept-in-machine-learning-5891628907ea](https://towardsdatascience.com/regularization-an-important-concept-in-machine-learning-5891628907ea)

- [https://www.deeplearningbook.org/contents/ml.html](https://www.deeplearningbook.org/contents/ml.html)

---

### Day 6

Which of the following are true about a **validation set**?

|Value| Description
|----:|:----
|1 | A validation set contains examples that the training algorithm does not observe 
|2 | No example from the test set can be used in the validation set
|3 | A validation set should always be constructed from the training set
|4 | A validation set should always be constructed from the test set

---

- A) 1 and 2
- B) 1, 2 and 3
- C) 1 and 4

<input type="text" placeholder="Type your answer" id="day6_choice" name="day6_choice"/>
<button type="submit" id="day6_submit" class="button">Send</button> 
<div id="day6_feedback"></div>

#### Resources
- [https://machinelearningmastery.com/difference-test-validation-datasets/](https://machinelearningmastery.com/difference-test-validation-datasets/)

- [https://www.deeplearningbook.org/contents/ml.html](https://www.deeplearningbook.org/contents/ml.html)

---

### Day 7

Which of the following techniques can be used to help compensate for small datasets?

- A) K-Fold cross-validation
- B) Using a simple classifier less susceptible to overfitting
- C) Use ensemble methods where voting between classifiers may compensate for over-learning
- D) Apply Transfer Learning
- E) Apply data augmentation
- F) All of the above

<input type="text" placeholder="Type your answer" id="day7_choice" name="day7_choice"/>
<button type="submit" id="day7_submit" class="button">Send</button> 
<div id="day7_feedback"></div>

#### Resources
- [https://www.kdnuggets.com/2019/06/5-ways-lack-data-machine-learning.html](https://www.kdnuggets.com/2019/06/5-ways-lack-data-machine-learning.html)

- [https://www.deeplearningbook.org/contents/ml.html](https://www.deeplearningbook.org/contents/ml.html)


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
    if (choice.value.toLowerCase() == answer) {
      feedback.innerHTML = "Correct!"
    } else {
      feedback.innerHTML = "Not quite."
    }
  }

  const days = [
    [1,"b", [String.raw`f : \R^n \to \R`]],
    [2,"c", [String.raw`x \in \R^n`, String.raw`\hat{x} \in \R^n`, String.raw`x`]],
    [3,"e", []],
    [4,"b",[]],
    [5,"d",[]],
    [6,"b",[]],
    [7,"f", []]
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

