# API Testing using Postman 🚀

This project contains automated API tests for the **[Restful Booker API](https://restful-booker.herokuapp.com/)** using **Postman**.  
The tests validate different endpoints like authentication, booking creation, booking details, update, and deletion.

---

## 📂 Project Structure

- **Booking API.postman_collection.json** → Postman collection containing all API requests and test scripts.
- **Booking_Environment.postman_environment.json** → Postman environment file with base URL, token, booking ID, and dynamic variables.
- **booking-report.html** → HTML report generated after running the tests.

---

## 🔑 Endpoints Tested

1. **Token Generator** → Generates authentication token.  
2. **Request For Details** → Fetches all booking IDs.  
3. **Create Booking** → Creates a new booking with random data.  
4. **Request For Specific Id** → Fetches details of a specific booking.  
5. **Update Booking** → Updates an existing booking.  
6. **Delete Booking** → Deletes a booking using booking ID.

---

## 🧪 Test Coverage

Each request validates:
- ✅ Status code (200 OK)  
- ✅ Response headers (`Content-Type`)  
- ✅ Response time (< 1000 ms)  
- ✅ Cookies (where applicable)  
- ✅ Response body structure (firstname, lastname, bookingid, etc.)  

---


---

## 👨‍💻 Author
**Md Nahid Hossain**  
📍 Comilla University | CSE Department  
