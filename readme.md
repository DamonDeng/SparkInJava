

package:

mvn package


submit:
spark-submit --master yarn --class com.mycompany.sparkinjava.App ./target/my-spark-in-java-1.0-SNAPSHOT.jar s3://testing.sig.damondeng.com/apptest/testing.txt s3://testing.sig.damondeng.com/apptest/newoutput/

