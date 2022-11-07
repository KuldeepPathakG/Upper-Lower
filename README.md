# Upper-Lower
Upper/Lower


def string_test(s):
  d={"UPPER_CASE":0, "lower_case":0}
  for c in s:
    if c.isupper():
      d["UPPER_CASE"]+=1
    elif c.islower():
      d["lower_case"]+=1
    else:
      pass
  print("Original String: ",s)
  print("Number of upper Case Characters: ", d["UPPER_CASE"])
  print("Number of Lower Case Characters: ", d["lower_case"])
string_test("The Quick Brown Fox")
