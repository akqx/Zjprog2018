### zjprog2018
## **Zawansowane języki programowania 2018**


| **w Javie**   | **w Ruby**    | **_do czego?_**                                                        |
| ------------- |:-------------:| ----------------------------------------------------------------------:|
| PMD           | Churn         | Sprawdzenie ile razy dana metoda się zmieniła,ABC complexity,duplikacje|
| SonarQube     | Robocop       | Poprawa stylu, formatowanie kodu, duplikacje, CodeSmell                                       |
| Cloc          | Cloc          | Zliczanie, linijek, komentarzy                                         |



## 3. Wyszukujemy w kodzie fragmenty WTF
	public static void main(String[] args) {
		int arr[] = { 3, 60, 35, 2, 45, 320, 5 }; // Array designators "[]" should be on the type, not the variable
		// porawione na int [] arr 
		
		BubbleSort b= new BubbleSort(); // Classes with only "static" methods should not be instantiated, poprawione(*A)
		
		System.out.println("Array Before Bubble Sort"); // Replace this use of System.out or System.err by a logger.
		// Logger log = Logger.getLogger("TestLogging");
		// log.info("Array Before Bubble Sort");
		
		for (int i = 0; i < arr.length; i++) {
			System.out.print(arr[i] + " ");
		}
		System.out.println();
		b.bubbleSort(arr); // (*A) BubbleSort.bubbleSort(arr)
		System.out.println("Array After Bubble Sort");
		for (int i = 0; i < arr.length; i++) {
			System.out.print(arr[i] + " ");
		}
	}

