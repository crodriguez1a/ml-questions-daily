## [Day 1](#day1)

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

## [Day 2](#day2)

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

## [Day 3](#day3)

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

## [Day 4](#day4)

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

## [Day 5](#day5)

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

### [Day 6](#day6)

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

### [Day 7](#day7)

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

---

### [Day 8](#day8)

It is common to say that algorithm *A* is better than algorithm *B* if the upper bound of the 95 percent conﬁdence interval for the error of algorithm *A* is less than the lower bound of the 95 percent conﬁdence interval for the error of algorithm *B*

- A) True
- B) False

<input type="text" placeholder="Type your answer" id="day8_choice" name="day8_choice"/>
<button type="submit" id="day8_submit" class="button">Send</button> 
<div id="day8_feedback"></div>

#### Resources

- [https://machinelearningmastery.com/calculate-the-bias-variance-trade-off/](https://machinelearningmastery.com/calculate-the-bias-variance-trade-off/)

- [https://www.deeplearningbook.org/contents/ml.html](https://www.deeplearningbook.org/contents/ml.html)

---

## [Day 9](#day9)

Distinguish between these two statistical approaches:

|1|2
|-----|-----
| This approach is based on estimating a single value of <span id="katex_day9_0" class="katex-formula"></span>, then making all predictions thereafter based on one estimate | This approach is to consider all possible values of <span id="katex_day9_1"></span> when making a prediction.

---

- A) 1 Frequentist Statistics, 2 Bayesian Statistics
- B) 1 Bayesian Statistics, 2 Frequentist Statistics
- C) 1 Einstein Statistics, 2 Bayesian Statistics

<input type="text" placeholder="Type your answer" id="day9_choice" name="day9_choice"/>
<button type="submit" id="day9_submit" class="button">Send</button> 
<div id="day9_feedback"></div>

#### Resources

- [https://www.deeplearningbook.org/contents/ml.html](https://www.deeplearningbook.org/contents/ml.html)

---

## [Day 10](#day10)

Unlike logistic regression, the support vector machine (SVM) does not provide probabilities, but only outputs a class identity.

- A) True
- B) False

<input type="text" placeholder="Type your answer" id="day10_choice" name="day10_choice"/>
<button type="submit" id="day10_submit" class="button">Send</button> 
<div id="day10_feedback"></div>

#### Resources

- [https://machinelearningmastery.com/a-tour-of-machine-learning-algorithms/](https://machinelearningmastery.com/a-tour-of-machine-learning-algorithms/)

- [https://www.deeplearningbook.org/contents/ml.html](https://www.deeplearningbook.org/contents/ml.html)

---

## [Day 11](#day11)

The category of algorithms that employ the kernel trick is known as:

- A) kernel machines
- B) kernel methods
- C) popcorn methods
- D) Both A and B

<input type="text" placeholder="Type your answer" id="day11_choice" name="day11_choice"/>
<button type="submit" id="day11_submit" class="button">Send</button> 
<div id="day11_feedback"></div>

#### Resources

- [https://machinelearningmastery.com/support-vector-machines-for-machine-learning/](https://machinelearningmastery.com/support-vector-machines-for-machine-learning/)

- [https://www.deeplearningbook.org/contents/ml.html](https://www.deeplearningbook.org/contents/ml.html)

---

## [Day 12](#day12)

When can supervised learning algorithms be useful?

- A) When computational resources are constrained
- B) When building intuition for more sophisticated learning algorithms
- C) When annotations are reliable and consistent
- D) All of the above

<input type="text" placeholder="Type your answer" id="day12_choice" name="day12_choice"/>
<button type="submit" id="day12_submit" class="button">Send</button> 
<div id="day12_feedback"></div>

### Resources

- [https://www.deeplearningbook.org/contents/ml.html](https://www.deeplearningbook.org/contents/ml.html)

- [https://www.cloudfactory.com/data-labeling-guide](https://www.cloudfactory.com/data-labeling-guide)

---

## [Day 13](#day13)

Which of the following could be accomplished with unsupervised learning?

- A) Density estimation
- B) Distribution sampling
- C) Data denoising
- D) Finding a manifold where data lies near
- E) Clustering into groups
- F) All of the above

<input type="text" placeholder="Type your answer" id="day13_choice" name="day13_choice"/>
<button type="submit" id="day13_submit" class="button">Send</button> 
<div id="day13_feedback"></div>

### Resources

- [https://www.deeplearningbook.org/contents/ml.html](https://www.deeplearningbook.org/contents/ml.html)

- [https://towardsdatascience.com/manifolds-in-data-science-a-brief-overview-2e9dde9437e5](https://towardsdatascience.com/manifolds-in-data-science-a-brief-overview-2e9dde9437e5)

---

## [Day 14](#day14)

Which of the following techniques are **not** useful towards simplifying data representation:

- A) lower-dimenstional representation
- B) sparse representation
- C) dense representation
- D) independent representation

<input type="text" placeholder="Type your answer" id="day14_choice" name="day14_choice"/>
<button type="submit" id="day14_submit" class="button">Send</button> 
<div id="day14_feedback"></div>

### Resources

- [https://www.deeplearningbook.org/contents/ml.html](https://www.deeplearningbook.org/contents/ml.html)

- [https://machinelearningmastery.com/sparse-matrices-for-machine-learning/](https://machinelearningmastery.com/sparse-matrices-for-machine-learning/)

---

## [Day 15](#day15)

Which of the following are true about Principal Component Analysis?

|Value| Description
|----:|:----
|1 | This algorithm provides a means of compressing data
|2 | It is an unsupervised learning algorithm that learns a representation of data
|3 | It learns a representation that has lower dimensionality than the original input
|4 | It learns a representation whose elements have no linear correlation with each other

---

- A) 1 and 2 are true
- B) 1 and 3 are true
- C) All are true

<input type="text" placeholder="Type your answer" id="day15_choice" name="day15_choice"/>
<button type="submit" id="day15_submit" class="button">Send</button> 
<div id="day15_feedback"></div>

### Resources

- [https://www.deeplearningbook.org/contents/ml.html](https://www.deeplearningbook.org/contents/ml.html)

- [https://machinelearningmastery.com/calculate-principal-component-analysis-scratch-python/](https://machinelearningmastery.com/calculate-principal-component-analysis-scratch-python/)

---

## [Day 16](#day16)

To achieve full independence, a representation learning algorithm must also remove the nonlinear relationships between variables

- A) True
- B) False

<input type="text" placeholder="Type your answer" id="day16_choice" name="day16_choice"/>
<button type="submit" id="day16_submit" class="button">Send</button> 
<div id="day16_feedback"></div>

---

## [Day 17](#day17)

Which of these are true about p-value?

- A) It can be defined as the probability of obtaining test results at least as extreme as the results actually observed
- B) It represents how likely it is to get a particular result when the null hypothesis is assumed to be true. 
- C) It is the probability of getting a sample like ours or more extreme than ours if the null hypothesis is correct
- D) All of the above

<input type="text" placeholder="Type your answer" id="day17_choice" name="day17_choice"/>
<button type="submit" id="day17_submit" class="button">Send</button> 
<div id="day17_feedback"></div>

---

## [Day 18](#day18)

Which of the following is true regarding singular value decomposition (SVD) and PCA?

- A) SVD is another name for PCA
- B) SVD is an alternative derivation of the principal components
- C) PCA and SVD are unrelated

<input type="text" placeholder="Type your answer" id="day18_choice" name="day18_choice"/>
<button type="submit" id="day18_submit" class="button">Send</button> 
<div id="day18_feedback"></div>

### Resources

- [https://www.deeplearningbook.org/contents/ml.html](https://www.deeplearningbook.org/contents/ml.html)

- [https://jonathan-hui.medium.com/machine-learning-singular-value-decomposition-svd-principal-component-analysis-pca-1d45e885e491#:~:text=What%20is%20the%20difference%20between,PCA%20skips%20less%20significant%20components.](https://jonathan-hui.medium.com/machine-learning-singular-value-decomposition-svd-principal-component-analysis-pca-1d45e885e491#:~:text=What%20is%20the%20difference%20between,PCA%20skips%20less%20significant%20components.)

---

## [Day 19](#day19)

Which of the following are advantages to using sparse representation(e.g. one hot encoding) in a clustering algorithm?

|Value| Description
|----:|:----
|1 | A natural conveyance of the idea that all examples in the same cluster are similar to each other
|2 | Confers the computational advantage that the entire representation may be captured by a single integer

---

- A) 1
- B) 2
- C) 1 and 2
- D) Neither 1 or 2

<input type="text" placeholder="Type your answer" id="day19_choice" name="day19_choice"/>
<button type="submit" id="day19_submit" class="button">Send</button> 
<div id="day19_feedback"></div>

### Resources

- [https://www.deeplearningbook.org/contents/ml.html](https://www.deeplearningbook.org/contents/ml.html)

---

## [Day 20](#day20)

Which of the following are common difficulties pertaining to clustering?

|Value| Description
|----:|:----
|1 | There is no single criterion that measures how well a clustering of the data corresponds to the real world
|2 | There may be many different clusterings that all correspond well to some property
|3 | It is possible to obtain a different, equally valid clustering not relveant to the task
|4 | It is difficult to measure Euclidean distance from a cluster centroid to the member of the cluster

---

- A) 1,3
- B) 1,2,3
- C) 2,4
- D) All

<input type="text" placeholder="Type your answer" id="day20_choice" name="day20_choice"/>
<button type="submit" id="day20_submit" class="button">Send</button> 
<div id="day20_feedback"></div>

### Resources

- [https://www.deeplearningbook.org/contents/ml.html](https://www.deeplearningbook.org/contents/ml.html)

- [https://www.freecodecamp.org/news/8-clustering-algorithms-in-machine-learning-that-all-data-scientists-should-know/](https://www.freecodecamp.org/news/8-clustering-algorithms-in-machine-learning-that-all-data-scientists-should-know/)

---

## [Day 21](#day21)

Nearly all of deep learning is powered by one very important algorithm: **stochastic gradient descent** (SGD).

- A) True
- B) False

<input type="text" placeholder="Type your answer" id="day21_choice" name="day21_choice"/>
<button type="submit" id="day21_submit" class="button">Send</button> 
<div id="day21_feedback"></div>

### Resources

- [https://www.deeplearningbook.org/contents/ml.html](https://www.deeplearningbook.org/contents/ml.html)

- [https://en.wikipedia.org/wiki/Stochastic_gradient_descent](https://en.wikipedia.org/wiki/Stochastic_gradient_descent)

---

## [Day 22](#day22)

A recurring problem in machine learning is that large training sets are necessary for good generalization, but large training sets are also more computationally expensive.

- A) False
- B) True

<input type="text" placeholder="Type your answer" id="day22_choice" name="day22_choice"/>
<button type="submit" id="day22_submit" class="button">Send</button> 
<div id="day22_feedback"></div>

### Resources

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
  
  // TODO: consider moving to data-attrs for katex
  const days = [
    [1,"b", [String.raw`f : \R^n \to \R`]],
    [2,"c", [String.raw`x \in \R^n`, String.raw`\hat{x} \in \R^n`, String.raw`x`]],
    [3,"e", []],
    [4,"b",[]],
    [5,"d",[]],
    [6,"b",[]],
    [7,"f", []],
    [8,"a", []],
    [9, "a", [String.raw`\theta`, String.raw`\theta`]],
    [10, "a", []],
    [11, "d", []],
    [12, "d", []],
    [13, "f", []],
    [14, "c", []],
    [15, "c", []],
    [16, "a", []],
    [17, "d", []],
    [18, "b", []],
    [19, "c", []],
    [20, "b", []],
    [21, "a", []],
    [22, "b", []]
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

