<<<<<<< HEAD
package test_package;
import java.util.Vector;

public class Cart {
	public static final int MAX_NUMBER_ORDERED = 20;
	private int qtyOrdered = 0;
	private Vector <DigitalVideoDisc> itemOrdered 
	= new Vector<> ( MAX_NUMBER_ORDERED );
	
	public void addDigitalVideoDisc (DigitalVideoDisc disc) {
		if (qtyOrdered == MAX_NUMBER_ORDERED) {
			System.out.println("Cannot add more to cart, your cart is full!");
			return;
		}
		itemOrdered.add(disc);
		qtyOrdered++;
		System.out.println("Disc (" + disc.getTitle()+ ") was added to your cart sucessfully!");
		if (qtyOrdered >= MAX_NUMBER_ORDERED-2) {
			System.out.println("Your cart is almost full! (" + qtyOrdered + "/" + MAX_NUMBER_ORDERED + ")");
		}
	}
	public void removeDigitalVideoDisc(DigitalVideoDisc disc) {
	    if (itemOrdered.remove(disc)) {
	        qtyOrdered--;
	        System.out.println("Disc  (" + disc.getTitle()+ ")  was removed from cart successfully!");
	    } else {
	        System.out.println("The disc was not found in the cart!");
	    }
	}
	public float totalCost() {
		float total=0;
		for (int i=0; i<itemOrdered.size(); i++) {
			total+= itemOrdered.get(i).getCost();
		}
		return total;
	}
}
=======
package test_package;
import java.util.Vector;

public class Cart {
	public static final int MAX_NUMBER_ORDERED = 20;
	private int qtyOrdered = 0;
	private Vector <DigitalVideoDisc> itemOrdered 
	= new Vector<> ( MAX_NUMBER_ORDERED );
	
	public void addDigitalVideoDisc (DigitalVideoDisc disc) {
		if (qtyOrdered == MAX_NUMBER_ORDERED) {
			System.out.println("Cannot add more to cart, your cart is full!");
			return;
		}
		itemOrdered.add(disc);
		qtyOrdered++;
		System.out.println("Disc (" + disc.getTitle()+ ") was added to your cart sucessfully!");
		if (qtyOrdered >= MAX_NUMBER_ORDERED-2) {
			System.out.println("Your cart is almost full! (" + qtyOrdered + "/" + MAX_NUMBER_ORDERED + ")");
		}
	}
	public void removeDigitalVideoDisc(DigitalVideoDisc disc) {
	    if (itemOrdered.remove(disc)) {
	        qtyOrdered--;
	        System.out.println("Disc  (" + disc.getTitle()+ ")  was removed from cart successfully!");
	    } else {
	        System.out.println("The disc was not found in the cart!");
	    }
	}
	public float totalCost() {
		float total=0;
		for (int i=0; i<itemOrdered.size(); i++) {
			total+= itemOrdered.get(i).getCost();
		}
		return total;
	}
}
>>>>>>> e9c05efd0c90db8b4aa8744d89af25f8ae47e28f
