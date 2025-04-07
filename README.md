# CelexWebApp  

?? **Plataforma de gesti�n administrativa para CELEX (CECyT 13 - IPN)**  
*Optimizando procesos acad�micos y administrativos para alumnos, profesores y administradores.*  

---

## ?? **�Qu� hace CelexWebApp?**  
Este sistema centraliza y agiliza tareas clave del curso de ingl�s **CELEX** en el **CECyT 13 del IPN**, permitiendo:  
- **Gesti�n de usuarios**: CRUD para alumnos, profesores y administradores.  
- **Generaci�n de documentos**: Reportes en PDF (ej: listas de asistencia, calificaciones).  
- **Acceso seguro**: Roles diferenciados (admin, profesor, alumno) con Identity.  
- **Integraci�n con servicios externos**: [Si hay APIs de pago o sistemas del IPN, agr�galos aqu�].  

---

## ?? **Tecnolog�as principales**  
- **Backend**:  
  ![.NET](https://img.shields.io/badge/.NET-8-%23512bd4)  
  - ASP.NET Core 8 (MVC)  
  - Entity Framework Core + SQL Server  
  - ASP.NET Core Identity (Autenticaci�n por roles)  
- **Despliegue**:  
  ![Azure](https://img.shields.io/badge/Azure-%230072C6?logo=microsoft-azure)  
  - Azure App Service  
  - Azure SQL Database (opcional)  

---

## ?? **Configuraci�n inicial**  

### **Requisitos**  
- [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)  
- SQL Server (Local o Azure)  
- Visual Studio 2022 / VS Code  

### **Pasos para ejecutar localmente**  
1. Clona el repositorio:  
   ```bash
   git clone https://github.com/tu-usuario/CelexWebApp.git
   cd CelexWebApp