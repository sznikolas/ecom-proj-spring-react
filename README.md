How to start react frontend (belongs to Telusko):
npm i
npm run dev
http://localhost:5173/

Backend:
It works with a H2 embedded database. You can populate data from data.sql file in the classpath, but needs to change its name from data1.sql to data.sql.
The initialization is already defined in the app.properties: spring.jpa.defer-datasource-initialization=true

