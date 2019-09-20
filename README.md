# check_arrayrotaion

package elclipse;

public class second_largest {

	public static void main(String[] args) {


		int a[]= {4,5,6,9,1,2,3};
		int count=0;
		for(int i=1;i<a.length;i++) {	
			if(a[i-1]<a[i]) {                         ///comparing elements
				count++;
			}	
		}
		System.out.print(count-1);

	}
}

////time complexity is O(n^2)
