# car-dealership-database
For this car dealership project, I created 7 tables.

The 7 tables were: salesperson, mechanic, customer, car, parts, invoice, and serviceTicket.

The tables for salesperson, mechanic, customer, car and parts were created first as they did not have foreign keys and I thought it would be easier to keep track of these tables and then work on invoice and serviceTicket last as they do have foreign keys.

Next, I created the invoice table that has foreign key's for customer_id, car_id and salesperson_id.

Finally, I created the serviceTicket table that has foreign keys for customer_id, car_id, mechanic_id and part_id.
