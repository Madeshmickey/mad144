<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Feedback Form</title>
</head>
<body>
    <h2>Student Feedback Form</h2>
    <form name="student_feedback_form" id="student_feedback_form" method="post">
        <label for="student_name">Your Name:</label><br>
        <input type="text" required name="name" id="student_name"/><br><br>

        <label for="student_email">Email:</label><br>
        <input type="email" required name="email" id="student_email"/><br><br>

        <label for="course_name">Course Name:</label><br>
        <input type="text" required name="course" id="course_name"/><br><br>

        <label>How do you rate the course?</label><br>
        <input type="radio" name="rating" id="rating_bad" value="bad" required>
        <label for="rating_bad">Bad</label><br>

        <input type="radio" name="rating" id="rating_good" value="good">
        <label for="rating_good">Good</label><br>

        <input type="radio" name="rating" id="rating_excellent" value="excellent">
        <label for="rating_excellent">Excellent!</label><br><br>

        <label for="feedback_comments">Comments:</label><br>
        <textarea required rows="4" name="comments" id="feedback_comments"></textarea><br><br>

        <button type="submit">Submit Feedback</button>
    </form>
</body>
</html>