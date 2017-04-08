import os
a=[]
while True:
    sub =raw_input("Physics, Chemistry or Math?(P,C,M?) ").lower()
    if sub=="p":
        s="2"
        break
    elif sub=="c":
        s="1"
        break
    elif sub=="m":
        s="9"
        break
    else:
        print"I/O error"
    
for i in range(2,17):
    x = "s"
    qp="qp"
    for z in range(1,5):
        for j in range (1,4):
            a.append("970{}_{}_{}_4{}".format(s,x+str(i),qp,j))
        if z==1:
            x="w"
        if z ==2:
            qp="ms"
        if z==3:
            x = "s"
        if z == 4:
            x="qp"
choice=raw_input("What year's past paper you want?(2-16) ")
qpm = raw_input("ms or qp? ")
zone =raw_input("41, 42 or 43? ")
tim = raw_input("w or s? ")

for lett in a:
    #print lett
    if choice  in lett:
        if qpm in lett:
            if zone in lett:
                if tim in lett:
                    print lett
                    os.system('start https://www.google.com/search?q={}'.format(lett))
