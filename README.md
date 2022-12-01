q1 = """Is Python case sensitiven when dealing with Identifiers?
a.True
b.False"""
q2 = """Python is a cross platfrom language True or False?
a.True
b.False"""
q3 = """ Is Python is a markup language? True or False?
a.True
b.False"""
q4 = """Python is a programming language True or False?
a.True
b.False"""
q5 = """Python runs on the chrome brower True or False?
a.True
b.False"""

questions = {q1:"a",q2:"a",q3:"b",q4:"a",q5:"a"}

name = input("enter your name:")
print("hello",name,"welcome to the python quiz world")
score=0
for i in questions:
    print(i)
    ans = input("enter the answer (a/b):")
    if ans==questions[i]:
        print("correct answer, you got 1 point")
        score=score+1
    else:
        print("Wrong answer,you lost 1 point")
        score=score-1
print("Final score is:",score)
    
    


