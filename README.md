# 2.222
import java.util.Date;
public class DateFormatExample {
   public static void main(String[] args) {
      Date date = new Date();
      System.out.printf("%tY-%tm-%td %tH:%tM:%tS %tZ", date, date, date, date, date, date);
   }
}
