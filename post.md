# Lab X: Doing stuff with hardware!

Please write a blog post describing your lab here.

This is just an example of how you might structure your blog post, feel free to edit as you wish. For example, you might divide the lab into different sections each with their own intro, instructions, results, and takeaways. Please see the rubric for details on how the post will be evaluated.

## Overview and Motivation

In this lab, we will design circuits that utilize memory in order to achieve increased functionality. Before this lab, we created different combinational circuits in which the outputs of the circuits were determined by the inputs directly. This means we weren't required to worry about memory, nor any notion of the sequence of operations that may have happened in the past.

This week, we will be working with Sequential Circuits. Sequential circuits introduce the idea of different states and being able to remember things about the previous input. The outputs can now be a function of both, inputs and previous internal state of the sequential circuit. In this lab, we will build a circuit that reads a binary number bit by bit and determines if that input (entire number) is divisible by 3. Each bit of the binary number will be clocked into the circuit sequentially, from the highest order bit to the lowest (left to right). As we recieve each bit, we must interpret it as this will equal to a different number than previous input/s and update our circuit's state accordingly.

To successfully be able to create this circuit, we need to make ourselves fimilar with Finite State Machine Design. Specifically, We need to successfully complete the following activities in order:-

    - Build a Finite State Machine (DFA) using a state transition diagram.

    - Build a State Table according to the FSM, and the JK FFs needed to track the state.

    -Design logic for the two combinational circuits, i.e. the next state and output.

    - Boolean Truth Table (function table) diagram.

    - After the truth table, minized K-map is needed for each output - each J, K, and out value.

    - And, last but not least, we need to test this in logisim to make sure everything is working as intended before starting to work on the lab directly.

## Materials

-PB-503 breadboard prototyping station

-Arduino

-7404 NOT gate IC

-7408 AND gate IC

-7486 XOR gate IC

-7476 JK Flip Flop IC

-Resistors

## Project Steps

## Testing

## Conclusion

This lab is where we learned the concept of memory and different states. In a systematic way, we learned to utilize Finite State Machine design which is very essential to form the backbone of sequential circuit implementation. We also got to apply the theoritical knowledge we learned in class about the sequential circuits like J-K Flip Flops e.t.c. and combining them with the combinational circuits in a practical scenerio. The project itself, building a circuit that reads a binary number that is inputted in a stream and determines if the input in decimal is divisible by 3, is very important and essential in a real world scenerio.

By going through the whole process of completing this lab, we not only honed our theory and technical skills but also learned how to debugg/troubleshooting our problems by backtracing, problem solving step by step, working with precision etc. We also got to have a deeper understanding of sequential circuits by spending our time with this lab as a group.
