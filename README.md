# CodeAlpha_hotel
import java.util.*;

class Room {
    private int roomNumber;
    private String category;
    private boolean isAvailable;

    public Room(int roomNumber, String category) {
        this.roomNumber = roomNumber;
        this.category = category;
        this.isAvailable = true;
    }

    public int getRoomNumber() {
        return roomNumber;
    }

    public String getCategory() {
        return category;
    }

    public boolean isAvailable() {
        return isAvailable;
    }

    public void setAvailable(boolean available) {
        isAvailable = available;
    }
}

class Reservation {
    private int reservationId;
    private int roomNumber;
    private String guestName;
    private Date checkInDate;
    private Date checkOutDate;

    public Reservation(int reservationId, int roomNumber, String guestName, Date checkInDate, Date checkOutDate) {
        this.reservationId = reservationId;
        this.roomNumber = roomNumber;
        this.guestName = guestName;
        this.checkInDate = checkInDate;
        this.checkOutDate = checkOutDate;
    }

    // Getters and setters
}

class Hotel {
    private List<Room> rooms;
    private List<Reservation> reservations;
    private int nextReservationId;

    public Hotel() {
        rooms = new ArrayList<>();
        reservations = new ArrayList<>();
        nextReservationId = 1;
        initializeRooms();
    }

    private void initializeRooms() {
        // Initialize rooms here (e.g., from a database or hard-coded)
    }

    public void displayAvailableRooms() {
        // Logic to display available rooms
    }

    public boolean makeReservation(int roomNumber, String guestName, Date checkInDate, Date checkOutDate) {
        // Logic to make a reservation
    }

    public void displayBookingDetails(int reservationId) {
        // Logic to display booking details
    }
}

public class hotel {
    public static void main(String[] args) {
        // Main logic of the program
    }
}
