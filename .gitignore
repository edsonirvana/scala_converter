/*libraries to converter unix_timestamp in timestamp begin*/
import java.util.Date
import java.text.SimpleDateFormat
/*libraries to converter unix_timestamp in timestamp end*/

/*libraries to converter timestamp in unix_timestamp begin*/
import org.apache.spark.sql.functions._
import org.apache.spark.sql.types._
/*libraries to converter timestamp in unix_timestamp end*/


/*function to converter unix_timestamp in timestamp begin*/

val imput: Int = 1480665459
val ts = $"imput" * 1000L
val df = new SimpleDateFormat("yyyy-MM-dd HH:mm:ss")
val date = df.format(ts)
println(date)
/*function to converter unix_timestamp in timestamp end*/
