import java.util*;

public class CruiseControl implements Response {
  private int speedSet = null;
  private int speedLimit = null;

  public void setSpeedSet(int speedSet) {
     this.speedSet = speedSet;
     while(this.speedSet <= 0) {
       
     }
  }
  public void setSpeedLimit(int speedLimit) {
    this.speedLimit = speedLimit;
  }
  public Response nextCommand() {
    
  }
  public void disable() {
    
  }
}
