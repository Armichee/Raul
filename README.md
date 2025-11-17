# <!DOCTYPE html>
<html>
<head>
    <title>Intranet Corporativa - Armiche</title>
    <style>
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; background-color: #f4f4f9; margin: 0; padding: 0; }
        header { background-color: #004a99; color: white; padding: 15px 40px; border-bottom: 3px solid #007bff; }
        header h1 { margin: 0; font-size: 1.8em; }
        nav { background-color: #e9ecef; padding: 10px 40px; border-bottom: 1px solid #ddd; }
        nav a { color: #004a99; text-decoration: none; margin-right: 20px; font-weight: 600; }
        nav a:hover { color: #007bff; }
        .container { display: flex; max-width: 1200px; margin: 20px auto; padding: 0 20px; }
        .main-content { flex: 3; padding: 20px; background-color: white; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.05); margin-right: 20px; }
        .sidebar { flex: 1; padding: 20px; background-color: #f0f8ff; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.05); }
        .sidebar h3 { color: #004a99; border-bottom: 1px solid #cce5ff; padding-bottom: 5px; }
        .identification { padding: 10px; background-color: #fff3cd; border: 1px solid #ffeeba; color: #856404; font-size: 0.9em; margin-top: 15px; }
        footer { background-color: #343a40; color: white; text-align: center; padding: 15px; position: fixed; bottom: 0; width: 100%; font-size: 0.8em; }
    </style>
</head>
<body>
    <header>
        <h1>Intranet Corporativa Soluciones SRC</h1>
    </header>
    <nav>
        <a href="#">Inicio</a>
        <a href="#">Recursos Humanos</a>
        <a href="#">Documentación</a>
    </nav>
    <div class="container">
        <div class="main-content">
            <h2>Bienvenido, Usuario VPN</h2>
            <p>Ha accedido de forma segura a los recursos internos de la empresa. La conexión a través de la Red Privada Virtual (VPN) está activa y lista para usar.</p>
            <h3>Noticias</h3>
            <ul>
                <li>**17/11/2025:** ¡Intranet V2.0 Desplegada!</li>
                <li>**05/11/2025:** Recordatorio: Acceso a la Intranet solo permitido vía VPN.</li>
            </ul>
        </div>        
        <div class="sidebar">
            <h3>Mi Perfil</h3>
            <p><strong>Estado:</strong> Conectado Remoto (VPN)</p>           
            <div class="identification">
                <strong>IDENTIFICADOR DEL PROYECTO:</strong><br>
                Este sitio es una simulación de Intranet creada por:
                <ul>
                    <li>**Alumno/Identificador:** **Armiche**</li>
                    <li>**Servidor Web:** Máquina B (Ubuntu/Apache2)</li>
                </ul>
            </div>
        </div>
    </div>
    <footer>
        &copy; 2025 Soluciones SRC | Departamento de Sistemas y Redes
    </footer>
</body>
</html>
