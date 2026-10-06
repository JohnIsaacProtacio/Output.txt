void main() {
  String studentName = 'John Isaac';
  int quizzes = 8;
  double examScore = 85.5;
  bool isPassed = true;

  int totalPoints = quizzes + 10;
  double averageScore = (quizzes + examScore) / 2;
  bool passedTheSubject = averageScore >= 75;

  print('Student Name: $studentName');
  print('Quiz Points: $quizzes');
  print('Exam Score: $examScore');
  print('Total Points: $totalPoints');
  print('Average Score: $averageScore');
  print('Passed the subject: $passedTheSubject');
  print('Initial passing status: $isPassed');
}
