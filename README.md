#คะแนน 0-49 grade 0 
#คะแนน 50-54 grade 1
#คะแนน 55-59 grade 1.5
#คะแนน 60-64 grade 2
#คะแนน 65-69 grade 2.5 
#คะแนน 70-74grade 3
#คะแนน 75-79 grade 3.5
#คะแนน >=80 grade 4

H=int(input("กรอกคะแนนการบ้าน"))
M=int(input("กรอกตะดนนสิบกลางภาค"))
F=int(input("กรอกคะแนนปลายภาค"))
#Athipbodi Nakphong 15
SC=H+M+F
print ("คะแนนรวม",SC)

if (SC<=49):
    G="0"
if (SC>=50)and(SC<<54):
    G="1"
if (SC>=55)and(SC<<59):
    G="1.5"
if (SC>=60)and(SC<<64):
    G="2"
if (SC>=65)and(SC<<69):
    G="2.5"
if (SC>=70)and(SC<<74):
    G="3"
if (SC>=75)and(SC<<79):
    G="3.5"
if (SC>=80):
    G="4"
#Athipbodi Nakphong 15  
print ("เกรดคุณคือ",G)
