# Remove-Duplicates-from-list-and-maintain-order-using-Java-8
Using java 8 feature
import java.util.stream.Collectors;
import java.util.*;
public class Main
{
	public static void main(String[] args) {
		//System.out.println("Hello World");
		List<String> list=Arrays.asList("Apple","Banana","cherry","Apple","Banana","Litchi");
		List<String> l=list.stream().distinct().toList();
		System.out.println(l);
	}
}
