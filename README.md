# if..elseif

var marks = prompt("Enter your marks : ")
if (marks >100 && marks< 0) // this logic has a problem because && operator will only work if the two conditions here are true
  document.write("invalid number");
else if (marks >= 80 && marks<=100)
    document.write("A+")
else if (marks >= 70 && marks<=79)
    document.write("A")
else if (marks >= 60 && marks<=69)
    document.write("A-")
else if (marks >= 50 && marks<=59)
    document.write("B")
else if (marks >= 40 && marks<=49)
    document.write("C")
else if (marks >= 33 && marks<= 39)
    document.write("D")
else
    document.write("Sorry. You are Failed");
