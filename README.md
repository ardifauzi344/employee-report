# employee-report
# Employee Report API

## 🛠 Teknologi:
- Spring Boot
- PostgreSQL
- JasperReports
- REST API

## 📌 Cara Menjalankan
1. **Clone repository**
   ```sh
   git clone https://github.com/username/employee-report.git
   cd employee-report
   ```

2. **Setup Database PostgreSQL**
   ```sql
   CREATE DATABASE employee_db;
   ```

3. **Konfigurasi `application.properties`**
   ```properties
   spring.datasource.url=jdbc:postgresql://localhost:5432/employee_db
   spring.datasource.username=postgres
   spring.datasource.password=yourpassword
   ```

4. **Jalankan Aplikasi**
   ```sh
   mvn spring-boot:run
   ```

5. **Gunakan API untuk Generate Laporan**
   ```sh
   http://localhost:8080/reports/employees?department=IT&startDate=2020-01-01&endDate=2023-12-31
   ```
