1)Open the file in wireshark, enter wireshark by double clicking the file in downloads

2)There are 22 packets when opened in wireshark, each containing payloads that are encoded in base 64

3)Identify patterns in the packets. Sort them based on time to single out the unique packets

4)Select the endings of each packets, and right click the blue highlighted portion in the output terminal

5)After using “show packet bytes”, convert everything to Base64

6)Find the starting flag picoCTF{

7)Continue by singling out the special payloads, namely the 12 byte and 4 byte payloads. The 4 byte payload will be the ending of the flag.

8)Open cyberchef and use “from Base64”

9)Copy the string of unconverted text

10)The string I got was:
cGljb0NURg==
ezF0X3c0cw==
bnRfdGg0dA==
XzM0c3lfdA==
YmhfNHJfZg==
MzE4ZGIyMg==
fQ==

11)After processing it turned into:
picoCTF{1t_w4snt_th4t_34sy_tbh_4r_f318db22}

12)This is the flag.

