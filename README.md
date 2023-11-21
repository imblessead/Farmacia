# Farmacia
Farmacia

package projetoFarmaciaUnipaulistana;

import java.awt.Font;

import javax.swing.JFrame;
import javax.swing.JLabel;
import javax.swing.JTextField;

public class FarmaciaUnipaulistana {
	
	JFrame f;
	JLabel l;
	JLabel l1;
	JLabel l2;
	JTextField tf1 , tf2;
	
	public FarmaciaUnipaulistana() {
		f= new JFrame("Farmacia Unipaulistana");
		f.setBounds(150,150,600,600);
		f.setVisible(true);
		f.setLayout(null);
		
		JLabel l= new JLabel("Login Farmacia Unipaulistana");
		l.setBounds (5,1,300,20);
		l.setFont(new Font("Arial",1,19));
		
		l1= new JLabel("Usuario");
		l1.setBounds(40,60,80,20);
		tf1 = new JTextField();
		
		
		tf1.setBounds(40,80,80,20);
		
		l2 = new JLabel("senha");
		l2.setBounds(40,100,80,20); 
		tf2 = new JTextField();
		tf2.setBounds(40, 120, 80, 20);
		
		
		f.add(l);
		f.add(l1);
		f.add(l2);
		f.add(tf1);
		f.add(tf2);
		f.setVisible(true);
		f.setLayout(null);
		
	}
 
	public static void main(String[] args) {
	new FarmaciaUnipaulistana ();
//Altera tamanho da fonte java swing
	}

}
