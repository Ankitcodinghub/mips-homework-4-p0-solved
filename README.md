# mips-homework-4-p0-solved
**TO GET THIS SOLUTION VISIT:** [MIPS Homework 4 P0 Solved](https://www.ankitcodinghub.com/product/mips-homework-4-p0-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;124624&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MIPS Homework 4 P0 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Instruction:

• The solutions should be submitted to Canvas. Email submissions (or other form of submissions) will not be accepted.

• Your submission should contain the following files:

o A “*.circ” file that contains the processor design.

o Four memory image file that contains the binary machine codes of the four testing programs, named as “Mem-1”, “Mem-2”, “Mem-3” and “Mem-4”, respectively. o The completed answer sheet (either WORD or PDF file).

• If you choose to answer the bonus question, you should submit two extra files (i.e., they should be separated files besides your solutions to Question 1-4).

o A “*.circ” file that contains the circuit for the bonus question.

o The completed answer sheet of the bonus question (either WORD or PDF file).

• You can use all build-in components provided in Logisim.

Question:

• This is a 16-bit processor. In particular, all registers are 16-bit, and each instruction is also

16-bit.

• The processor supports the following instructions.

Name Format Functionality

li li $r1, x load immediate number to one register ($r1)

add add $r1, $r2, $r3 add two register numbers ($r2 and $r3) and store the result in one register ($r1)

and and $r1, $r2, $r3 bit-wise logical AND of two register numbers ($r2 and $r3), and store the result in a register ($r1)

or or $r1, $r2, $r3 bit-wise logical OR of two register numbers ($r2 and $r3), and store the result in a register ($r1)

load ld $r1, $r2 load a 16-bit number from data memory to a register ($r1). The data memory address is the value in a register ($r2)

store st $r1, $r2 load a 16-bit number from a register ($r1) to data memory. The data memory address is the value in a register ($r2)

move move $r1, $r2 copy the value of one register ($r2) to another register ($r1)

addi addi $r1, $r2, x add a register number ($r2) and an immediate number (x), and

store the result in one register ($r1)

and i andi $r1, $r2, x bit-wise logical AND of a register number ($r2) and an immediate number x, and store the result in a register ($r1)

ori ori $r1, $r2, x bit-wise logical OR of a register number ($r2) and an immediate number x, and store the result in a register ($r1)

ble ble $r1, $r2, x if the first register number ($r1) is smaller than or equal to the

second register number ($r2), then jump to address (PC + x).

bne bne $r1, $r2, x if the first register number ($r1) does not equal the second

register number ($r2), then jump to address (PC + x).

jump jump x Jump to address (PC + x).

call cal x Jump to address (PC + x), where x is an immediate number, and at the same time the address of the next instruction to a special register $ra ($ra is not one of the 8 general registers $r1 — r8).

rtn rtn Jump to address stored in $ra.

halt halt all registers (including PC, the 8 general purpose registers and all other registers) in the processor are disabled (so the processor halts).

You should design the instruction set for the processor. In particular, you should decide the formats Assignment Project Exam Help of different types of instructions and design the coding for each instruction.

Test Program 1:

.text

li $r1, 1 li $r2, 2 li $r3, 10 add $r2, $r1, $r2 ble $r2, $r3, -1 #jump to the previous instruction if the condition is satisfied halt

Test Program 2:

.text

li $r1, 6 li $r2, 5 andi $r3, $r1, 3 ori $r4, $r3, 8 halt

Test Program 3:

.text

li $r1, 6 li $r2, 5 and $r3, $r1, $r2 li $r8, 0 store $r3, $r8 or $r4, $r1, $r2 li $r8, 1 store $r4, $r8 li $r8, 1 load $r7, $r8 halt

Test Program 4:

.text

li $r1, 6 li $r2, 4 call 7 move $r4, $r3

li $r1, 7 li $r2, 8 call 3 move $r5, $r3 jump 3 add $r3, $r1, $r2 rtn halt

Bonus Question:

Build a processor that fulfils all the requirements above, while using a five-stage pipeline and resolve the control hazards and data hazards properly:

1. IF: instruction fetch stage

2. ID: instruction decode &amp; register file read stage

3. EX: execution stage

4. MEM: memory access stage

5. WB: write-back stage

Your pipelined processor should use the same instruction set as in the above question, and be able to execute the above testing programs using the same memory images.
