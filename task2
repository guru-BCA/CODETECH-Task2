class StudentGrades:
    def __init__(self, student_name):
        self.student_name = student_name
        self.grades = {}

    def add_grade(self, subject, grade):
        if subject in self.grades:
            self.grades[subject].append(grade)
        else:
            self.grades[subject] = [grade]

    def calculate_average(self):
        total_grades = 0
        count = 0
        for grades in self.grades.values():
            total_grades += sum(grades)
            count += len(grades)
        return total_grades / count if count > 0 else 0

    def determine_letter_grade(self, average):
        if average >= 90:
            return 'A'
        elif average >= 80:
            return 'B'
        elif average >= 70:
            return 'C'
        elif average >= 60:
            return 'D'
        else:
            return 'F'

    def calculate_gpa(self, average):
        if average >= 90:
            return 4.0
        elif average >= 80:
            return 3.0
        elif average >= 70:
            return 2.0
        elif average >= 60:
            return 1.0
        else:
            return 0.0

    def display_report(self):
        print(f"Student: {self.student_name}")
        print("Grades:")
        for subject, grades in self.grades.items():
            print(f"  {subject}: {grades}")
        average = self.calculate_average()
        letter_grade = self.determine_letter_grade(average)
        gpa = self.calculate_gpa(average)
        print(f"Average Grade: {average:.2f}")
        print(f"Letter Grade: {letter_grade}")
        print(f"GPA: {gpa:.2f}")

def main():
    student_name = input("Enter the student's name: ")
    student = StudentGrades(student_name)

    while True:
        subject = input("Enter the subject (or 'done' to finish): ")
        if subject.lower() == 'done':
            break
        try:
            grade = float(input(f"Enter the grade for {subject}: "))
            if 0 <= grade <= 100:
                student.add_grade(subject, grade)
            else:
                print("Please enter a valid grade between 0 and 100.")
        except ValueError:
            print("Invalid input. Please enter a numeric grade.")

    student.display_report()


main()
