# Project-GitHub-Fishing
Replica of GitHub's login page. Save the data entered by the 'user' in a database, with the purpose of collecting the data without anyone noticing.

markdown
#  Simulador de Phishing Ético ⚠️


![GitHub Security](https://github.githubassets.com/images/modules/logos_page/Octocat.png)

## 📌 Descripción Técnica
Réplica HTML/CSS de la página de login de GitHub con:
- Almacenamiento en Firebase Realtime Database (solo demostración)
- Interfaz visual idéntica al original
- Mecanismo educativo para mostrar cómo operan los ataques phishing

## 🛡️ Uso Aprobado
```diff
+ USO PERMITIDO:  
- Entornos educativos controlados  
- Cursos de seguridad informática  
- Auditorías éticas autorizadas  

- PROHIBIDO:  
+ Usar con credenciales reales  
+ Desplegar en entornos públicos  
+ Almacenar datos personales reales  
🔧 Configuración Rápida
Pre-requisitos:

Cuenta Firebase (modo prueba)

Navegador moderno (Chrome/Firefox)

Configura Firebase (/js/firebase-config.js):

javascript
const firebaseConfig = {
  apiKey: "{{TU_API_KEY}}",
  authDomain: "{{TU_PROYECTO}}.firebaseapp.com",
  databaseURL: "https://{{TU_PROYECTO}}-default-rtdb.firebaseio.com",
  projectId: "{{TU_PROYECTO}}",
  storageBucket: "{{TU_PROYECTO}}.appspot.com",
  messagingSenderId: "{{TU_SENDER_ID}}",
  appId: "{{TU_APP_ID}}"
};
Datos de Prueba (/data/demo_credentials.json):

json
[
  {"user": "student1@demo.edu", "pass": "Demo123!"},
  {"user": "test_user@fake.com", "pass": "PasswordFake"}
]
⚖️ Cláusula Legal (Debe incluirse)
"Este material se provee únicamente con fines educativos. El equipo no se hace responsable por uso indebido. Todo el código debe ejecutarse en entornos controlados con consentimiento explícito de los participantes."

📊 Métricas Educativas
Intento Simulado	Usuario Fake	Contraseña Fake	Tiempo Exposición
1	user1@training.org	Training2024	2 min
2	demo@security.lab	SecurePass!	1.5 min
📚 Recursos Adicionales
Cómo identificar phishing

Reportar phishing real a GitHub

👥 Responsables
Supervisor Académico: {{Nombre del Profesor}}

Equipo de Desarrollo:

{{Nombre 1}} ({{Rol}})

{{Nombre 2}} ({{Rol}})

✉️ Contacto Ético: {{email_institucional@dominio.edu}}
🔒 Última Actualización: {{DD/MM/AAAA}}

text

### 🔄 Archivos Adicionales Necesarios:

1. **LICENSE** (Recomiendo [MIT License](https://opensource.org/license/mit/)):
   ```text
   Copyright {{YYYY}} {{Nombre del Autor}}

   Permission is hereby granted...
/legal/disclaimer.md:

markdown
## Aviso Legal Completo
Este proyecto cumple con:
- Artículo 197 del Código Penal (sobre protección de datos)
- Políticas éticas de {{Tu Institución}}
/docs/ethical_guidelines.md:

markdown
### Protocolo para Demostraciones:
1. Usar solo en redes aisladas
2. Notificar a participantes: "Esto es una simulación"
3. Borrar datos después de cada sesión
