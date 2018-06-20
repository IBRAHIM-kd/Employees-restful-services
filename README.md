# Employees-restful-services
Applying full Restful services on Employee Information System 

- THIS PROJECTS IS BASE ON EMPLOYEES INFORMATION WITH RESTFUL SERVICES API PRACTICES 

  how to run this project
  
  git clone https://github.com/IBRAHIM-kd/Employees-restful-services.git
  
  cd Employees-restful-services
  
  mvn clean install
  
  mvn spring-boot:run 
  
  
  1  -  curl -X POST http://localhost:8080/api-token-auth/ --data 
        "username=employees&password=employees"
		

  2  -  curl  http://localhost:8080/api/employees/	
  
  
  3  -  curl  http://localhost:8080/api/employees/	
  
  
  4  -  curl  http://localhost:8080/employees?firstName=ar&gender=MALE'
  
  
  5  -  curl  http://localhost:8080/api/employees/user/