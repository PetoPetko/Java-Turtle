# Java-Turtle
Java imagine like turtle.

This is lib that alow you to use turtle graphics in java!

All what you need to do is download and import lib and make your main class looks like this:
<PRE>
package package;

import static ugp.org.Turtle.Actions.*;

import javafx.stage.Stage;
import ugp.org.Turtle.ShowTurtle;
import ugp.org.Turtle.Turtle;

public class Main extends ShowTurtle 
{
	@Override
	protected void Program(Turtle t, Stage s) 
	{
		//Write turtle commands here!
		/*Example:*/t.Foreward(100);
	}
}
</PRE>
