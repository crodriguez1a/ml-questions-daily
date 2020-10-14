## Day 1

Name the following machine learning task:

*"...the computer program is aksed to predict a numerical value given some input. To solve this task, the learning algorithm is asked output a function"*

![day1_function1](images/Day1_Function1.png "Day 1 - Function 1")

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
