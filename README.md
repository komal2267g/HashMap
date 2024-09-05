# HashMap
#simple code using java
import java.util.HashMap;
import java.util.Map;
public class Main {
    public static void main(String[] args) {
        Map<String,Integer >map= new HashMap<>();
        map.put("apple", 100);
        map.put("apple",200);
         System.out.println("update value for 'banana':" + map.get("apple"));
    }
}
         

       
