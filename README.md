# Pytho_Data-Structures-List

## Find out Who scored highest marks in Python?
##  Step1: Select name of student and marks in Python
##  Step2: Store filtered name and marks in another list
##  Step3: Sort list. (Kept marks as first index)
##  Step4: Get final index of sorted list

student_marks = [["Name", ["Statistics", "Python", "SQL", "ML", "Deeplearning"]], 
                 ["Ananya", [41, 34, 45, 55, 63]], 
                 ['Akash', [42, 23, 34, 44, 53]],
                 ['Rahul', [32, 23, 13, 54, 67]], 
                 ['Mukesh', [23, 82, 23, 63, 34]], 
                 ['Pranav', [21, 23, 25, 56, 56]]]
student_marks

##  Step1: Select name of student and marks in Python
for student in student_marks[1:]:
    name = student[0]
    mark = student[1][1]
    print(name, mark)

##  Step2: Store filtered name and marks in another list
student_marks_python = []
for student in student_mark[1:]:
    name = student[0]
    python = student[1][1]
    student_marks_python.append([python, name])
student_marks_python

##  Step3: Sort list. (Kept marks as first index)
student_marks_python.sort()
print(student_marks_python)

##  Step4: Get final index of sorted list
student_marks_python[-1]


### Please write every step in single cell(jupyter)
