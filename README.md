# RotatedArray
You have a sorted array of N length which was rotated, e.g. [4, 5, 6, 7, 8, 
9, 10, 1, 2, 3].<br/>
Rotated means that we move first M numbers to the end.<br/>
You need to find index of target number using binary search.<br/>
In case there is no such number in array, return -1;<br/>
All numbers in array are unique.<br/>
Use TDD approach.<br/><br/>
0<=N<br/>
0<=M<=N<br/>
Time complexity should be O(logN).<br/><br/>
**Signature:**<br/>

	package ua.goit.alg;
	
	public class RotatedArrays {
		public static int binarySearch(int[] array, int target) {
		
		}
	}

**Example:**<br/>
input [4, 5, 6, 7, 8 ,9, 10, 1, 2, 3], 5<br/>
output 1