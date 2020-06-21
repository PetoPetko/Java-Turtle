# Java-Turtle
Java imagine like turtle.

This is lib that alows you to use turtle graphics in java!

All what you need to do is download and import lib and make your main class looks like this:
<PRE>
package some.awesome.package;

import javafx.stage.Stage;
import ugp.org.Turtle.Actions;
import ugp.org.Turtle.ShowTurtle;
import ugp.org.Turtle.Turtle;

public class Main extends ShowTurtle 
{
	public static void main(String[] args)
	{
		launch(args);
	}
	
	@Override
	protected void Program(Turtle t, Stage s) 
	{
		//Write your turtle commands here!
		
		//For example, this will draw "HI!"
		Actions.DrawH(t, 100);
		t.penUp();
		t.Right(90);
		t.Forward(110);
		t.Right(90);
		t.penDown();
		Actions.DrawI(t, 100);
		t.Left(90);
		t.penUp();
		t.Forward(80);
		t.penDown();
		t.Left(90);
		Actions.DrawExclMark(t, 100);
	}
}
</PRE>
