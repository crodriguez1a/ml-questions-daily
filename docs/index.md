<!DOCTYPE html>
<!-- KaTeX requires the use of the HTML5 doctype. Without it, KaTeX may not render properly -->
<html>
  <head>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/katex@0.12.0/dist/katex.min.css" integrity="sha384-AfEj0r4/OFrOo5t7NnNe46zW/tFgW6x/bCJG8FqQCEo3+Aro6EYUG4+cU+KJWu/X" crossorigin="anonymous">

    <!-- The loading of KaTeX is deferred to speed up page rendering -->
    <script defer src="https://cdn.jsdelivr.net/npm/katex@0.12.0/dist/katex.min.js" integrity="sha384-g7c+Jr9ZivxKLnZTDUhnkOnsh30B4H0rpLUpJ4jAIKs4fnJI+sEnkvrMWph2EDg4" crossorigin="anonymous"></script>

    <!-- To automatically render math in text elements, include the auto-render extension: -->
    <script defer src="https://cdn.jsdelivr.net/npm/katex@0.12.0/dist/contrib/auto-render.min.js" integrity="sha384-mll67QQFJfxn0IYznZYonOWZ644AWYC+Pt2cHqMaRhXVrursRwvLnLaebdGIlYNa" crossorigin="anonymous"
        onload="renderMathInElement(document.body);"></script>
  </head>
  ...
</html>

## Day 1

Name the following machine learning task:

*"...the computer program is aksed to predict a numerical value given some input. To solve this task, the learning algorithm is asked output a function"*

![day1_function1](images/Day1_Function1.png "Day 1 - Function 1")

<script>
katex.render("\f\mathchoice :: \R^n \to \R", element, {
    throwOnError: false
});
</script>

- A) Classification
- B) Regression
- C) Structured output

Answer: <input type="text" placeholder="Type your answer" id="day1_choice" name="day1_choice"/>
<button type="submit" id="day1_submit" class="button">Send</button> 
<div id="day1_feedback"></div>


<script>
const selectAnswer = (answer, submit_id, choice_id, feedback_id) => {
  const feedback = document.getElementById(feedback_id)
  const choice = document.getElementById(choice_id);
  if (choice.value.toLowerCase() == answer) {
    feedback.innerHTML = "Correct!"
  } else {
    feedback.innerHTML = "Not quite...try again."
  }
}

const days = [[1,"b"]]
for (let i in  days) {
  [id, ans] =  days[i]
  document.getElementById("day" + id + "_submit").addEventListener(("click"), () => {
    selectAnswer(ans, "day" + id + "_submit", "day" + id + "_choice", "day" + id + "_feedback")
  });
 }
</script>
