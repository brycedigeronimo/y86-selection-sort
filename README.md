Author: Bryce Di Geronimo

Description: Selection sort is implemented using a y86 processor as described in Computer Systems: A Programmers Perspective by Bryant and O'Hallaron

Instructions:
Write a Y86-64 program that sorts an array of longs.
	• Allocate a hardcoded input array with at least 10 entries.
	• Implement a swap procedure equivalent to the following C code:
	void swap(long *xp, long *yp) {
	 long t0 = *xp;
	 long t1 = *yp;
	 *xp = t1;
	 *yp = t0;
	}
	• Implement a sort procedure that sorts the input array using Selection Sort. Your
	sort procedure should call your swap procedure to perform the swaps and it should sort
	the array in place – there’s no need to allocate additional memory for an output array.
	• Implement a main procedure to call your sort procedure, passing the input array
	and array length as arguments.


link to y86-64 simulator: https://boginw.github.io/js-y86-64/