# The Final Project

## Intercepting Traffic and Interpreting Brainfuck

### Project Statement:
*Alice wants to communicate with Bob from halfway across the world. She sends him a Brainfuck script over a network. However, the nosy Eve manages to intercept this network and capture all the network packets of their communication. She extracts the Brainfuck script and, using her very own interpreter, runs the script successfully.*

### What you actually need to do (in simple English 🤡):
There are essentially three components of this project.
1. **Socket Programming**: First, you need to create and set up the client (Alice) and the server (Bob) programs. 
2. **Wireshark**: Next, start a packet capture on Wireshark. Take any Brainfuck program and send it from the client (Alice) to the server (Bob). Once completed, terminate the packet capture. Now, assume the role of Eve and extract the Brainfuck program from the PCAP file you have just created.
3. **Brainfuck Interpreter**: Use Python, C, or C++ to write a program that takes in the name of a file containing Brainfuck code and executes the code in that file. You are essentially creating a program to "execute" Brainfuck code. To learn about how Brainfuck code is written, and to see examples, refer to [this](https://en.wikipedia.org/wiki/Brainfuck) page. (You may assume that the Brainfuck code given to the program has no errors.)

### Submission Instructions


### Submission Link
You are required to submit the following:
- client and server programs
- PCAP file with the captured network traffic
- Brainfuck Interpreter

Add all files related to your project submission in a public GitHub repository or a publicly viewable Google Drive Folder. Submit the link to the GitHub repository or Google Drive Folder here: https://forms.gle/fFGtc1CxU8QVvRwGA
