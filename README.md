# zjprog2018
**Zawansowane języki programowania 2018**


| **w Javie**   | **w Ruby**    | **_do czego?_**                                                        |
| ------------- |:-------------:| ----------------------------------------------------------------------:|
| PMD           | Churn         | Sprawdzenie ile razy dana metoda się zmieniła,ABC complexity,duplikacje|
| SonarQube     | Robocop       | Poprawa stylu, formatowanie kodu, duplikacje, CodeSmell                                       |
| Cloc          | Cloc          | Zliczanie, linijek, komentarzy                                         |




'''
public class App {
	public static void main(String[] args) {
		int arr[] = { 3, 60, 35, 2, 45, 320, 5 };
		
		BubbleSort b= new BubbleSort();
		
		System.out.println("Array Before Bubble Sort");
		for (int i = 0; i < arr.length; i++) {
			System.out.print(arr[i] + " ");
		}
		System.out.println();
		b.bubbleSort(arr);// sorting array elements using bubble sort
		System.out.println("Array After Bubble Sort");
		for (int i = 0; i < arr.length; i++) {
			System.out.print(arr[i] + " ");
		}
	}
}
'''
