# prova
import java.awt.*;

public class MyApplication8 {
public static void main (String[] args) {

Choice l = new Choice();
l.addItem("Item 1");
l.addItem("Item 2");
l.addItem("Item 3");
TextArea ta = new TextArea(5,20);
TextField tf = new TextField();
Label lb = new Label("This is an example");

Frame f = new Frame("Some sample");
f.setLayout(new GridLayout(2,2));
f.setLocation(100,100);
f.add(lb);
f.add(l);
f.add(tf);
f.add(ta);



f.pack(); //serve ad adattarsi ai componenti inseriti
f.setVisible(true);
}
}
