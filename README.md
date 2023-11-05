# CT Amplifier with DC output

# What is it?
This is a four channel Amplifier for Current Transformators like the SCT-013-10
# Why do i need it?
If you want to attach a current transformator to an ESP32 you might have problems sampling the voltage. Esp. in the ESP Easy this is not easy.
With this solution you just connect your power clamp to the amplifier and the amplifier outputs a voltage which represents the alternating input from the ct.
# How does the circuit look like?
## Have a look at this nice simulation:
https://www.falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWEBmATNA7AhAOBjVIAWfbEBANnJCOXIFMBaMMAKADcRUNUViueNMFUjhyoiKKnQErAA7hUOPkUXKiwlFC6sA7mpUDeyfpD1GhVMEstRzROLYQYqGkawAm5aykLkXvqK8YAByzizm3LxuNI4xZgoUgmiiSdGadEHmaYH+VCl2+g6iMcUoyO4AThYmqjG12sgmcKzVMagOeVydEvAthACcXQXOrprSfZAD0zOzc0PIsHBEFGAYAxQIyDOZ4KwAhrYjPgXKYEjMSGCT0hQUkOtEGMQVqKibyowwTTy4OAMYMAObAYDDgSbmUbdURQgpmIqaKJHUz2DIVWKiJruBFUDolRGCeFdGI5eKsAD2YgoqgkbwGmNgJjAJmQ1jAAyBRBpS0gki4IDBZiAA
# How does it work?
The schematics is a standard precission rectifier buil with an operation amplifier, two resistors, a diode and a capacity. That's easy.
# Is there a working schematics and a board design?
Yes! 
This is the eagle schamatic and the eagle board
![image|300](https://github.com/olfried/Current-Transformator-Amplifier-with-DC-Output/assets/1424287/fb836c10-add7-444c-9d68-6aecdde90775|width=100)
![image](https://github.com/olfried/Current-Transformator-Amplifier-with-DC-Output/assets/1424287/52c06ced-3bea-4f8c-8aae-537ad149ca01)
![image](https://github.com/olfried/Current-Transformator-Amplifier-with-DC-Output/assets/1424287/b0e222b8-5088-4c5a-83d9-b79cc6d68dd8)

# Can i get a working device?
No, but you can get a kit consisting of:
- The PCB
- An operation amplifier, "MCP604" with socket
- Eight Resistors (4x33k, 4x100k)
- Four schottky diodes (4 x BAT46)
- Four electrolytic capacitor (4 x 10uF)

If you are interested, let me know:
olaf@ramge.de
