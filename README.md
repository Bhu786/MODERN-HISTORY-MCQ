# MODERN-HISTORY-MCQ


## Question 1:
What is the capital of France?

- [ ] Berlin
- [ ] Madrid
- [x] Paris
- [ ] Rome

---

## Question 2:
Which programming language is primarily used for web development?

- [x] JavaScript
- [ ] Python
- [ ] C++
- [ ] Java


## **Question 11:**
Which are primary colors?

- <span style="color:green">[x]</span> Red
- <span style="color:red">[ ]</span> Purple
- <span style="color:green">[x]</span> Blue
- <span style="color:red">[ ]</span> Orange



## Question 1:  
**What is the capital of France?**

<form>
    <input type="radio" name="q1" id="q1-option1" onclick="checkAnswer('q1', false)"> Berlin<br>
    <input type="radio" name="q1" id="q1-option2" onclick="checkAnswer('q1', false)"> Madrid<br>
    <input type="radio" name="q1" id="q1-option3" onclick="checkAnswer('q1', true)"> Paris<br>
    <input type="radio" name="q1" id="q1-option4" onclick="checkAnswer('q1', false)"> Rome<br>
</form>

<p id="q1-answer" style="display:none; color: green;">Correct! Paris is the capital of France.</p>
<p id="q1-wrong" style="display:none; color: red;">Sorry, that's incorrect. Try again!</p>

---

## Question 2:  
**Which planet is known as the Red Planet?**

<form>
    <input type="radio" name="q2" id="q2-option1" onclick="checkAnswer('q2', false)"> Earth<br>
    <input type="radio" name="q2" id="q2-option2" onclick="checkAnswer('q2', true)"> Mars<br>
    <input type="radio" name="q2" id="q2-option3" onclick="checkAnswer('q2', false)"> Venus<br>
    <input type="radio" name="q2" id="q2-option4" onclick="checkAnswer('q2', false)"> Jupiter<br>
</form>

<p id="q2-answer" style="display:none; color: green;">Correct! Mars is known as the Red Planet.</p>
<p id="q2-wrong" style="display:none; color: red;">Sorry, that's incorrect. Try again!</p>

---

<script>
function checkAnswer(question, isCorrect) {
    var correctAnswer = document.getElementById(question + '-answer');
    var wrongAnswer = document.getElementById(question + '-wrong');
    
    if (isCorrect) {
        correctAnswer.style.display = 'block';
        wrongAnswer.style.display = 'none';
    } else {
        wrongAnswer.style.display = 'block';
        correctAnswer.style.display = 'none';
    }
}
</script>

