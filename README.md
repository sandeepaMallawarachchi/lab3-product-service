# Lab 3

## Part 1 – Creating a Spring Boot Microservice

<img width="1469" height="878" alt="Screenshot 2026-02-16 at 11 46 07 AM" src="https://github.com/user-attachments/assets/3658b9d3-8031-4a32-8ab8-e0d8f1b01533" />


## Part 2 – Implementing REST APIs

```
  cloudedesignwebgmail.com@sandeepas-MacBook-Air product-service % curl -X POST http://localhost:8080/api/products \
    -H "Content-Type: application/json" \
    -d '{"name":"Mouse","price":2500}'
  
  {"name":"Mouse","price":2500.0,"id":1}%                                                                                                                                         
  cloudedesignwebgmail.com@sandeepas-MacBook-Air product-service % curl http://localhost:8080/api/products
  
  [{"name":"Mouse","price":2500.0,"id":1}]%                                                                                                                                       
  cloudedesignwebgmail.com@sandeepas-MacBook-Air product-service % curl http://localhost:8080/api/products/1
  
  {"name":"Mouse","price":2500.0,"id":1}%                                                                                                                                         
  cloudedesignwebgmail.com@sandeepas-MacBook-Air product-service % curl -X DELETE http://localhost:8080/api/products/1
  
  cloudedesignwebgmail.com@sandeepas-MacBook-Air product-service % curl http://localhost:8080/api/products
  
  []%
```

## Part 3 – Using an In-Memory Database (H2)

<img width="997" height="422" alt="Screenshot 2026-02-16 at 11 48 59 AM" src="https://github.com/user-attachments/assets/d9d2403b-eb31-4a22-a097-f0d7795faf9b" />

## Part 4 – Enabling Swagger (OpenAPI)

<img width="745" height="787" alt="Screenshot 2026-02-16 at 11 52 55 AM" src="https://github.com/user-attachments/assets/2ab4e109-3fe1-4976-8a3e-214d9df7cf05" />


<img width="743" height="801" alt="Screenshot 2026-02-16 at 11 52 35 AM" src="https://github.com/user-attachments/assets/10670455-f896-4cb5-b62a-ed2b3a1c2cf6" />
