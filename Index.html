<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Login y Registro</title>
<style>
body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background: #0f172a;
}
#authPage {
    display: flex;
    flex-direction: column;
    align-items: center;
    background: #1e293b;
    padding: 50px;
    border-radius: 20px;
    box-shadow: 0 10px 20px rgba(0,0,0,0.5);
    width: 320px;
}
#authPage h2 {
    color: #38bdf8;
    margin-bottom: 30px;
    font-size: 28px;
}
input {
    width: 100%;
    padding: 12px;
    margin-bottom: 15px;
    border-radius: 8px;
    border: none;
    outline: none;
}
button {
    width: 100%;
    padding: 12px;
    border: none;
    border-radius: 8px;
    background-color: #38bdf8;
    color: #0f172a;
    font-weight: bold;
    cursor: pointer;
    margin-bottom: 15px;
}
button:hover {
    background-color: #0ea5e9;
}
#toggleAuth {
    cursor: pointer;
    color: #38bdf8;
    text-decoration: underline;
}
</style>
</head>
<body>

<div id="authPage">
    <h2 id="authTitle">Registro</h2>
    <input id="authUser" type="text" placeholder="Correo">
    <input id="authPass" type="password" placeholder="Contraseña">
    <button id="authBtn">Registrarse</button>
    <p id="toggleAuth">¿Ya tienes cuenta? Inicia sesión</p>
</div>

<script>
let isLogin = false;

function updateAuthUI(){
    document.getElementById("authTitle").textContent = isLogin ? "Iniciar sesión" : "Registro";
    document.getElementById("authBtn").textContent = isLogin ? "Entrar" : "Registrarse";
    document.getElementById("toggleAuth").textContent = isLogin ? "¿No tienes cuenta? Regístrate" : "¿Ya tienes cuenta? Inicia sesión";
}

document.getElementById("toggleAuth").addEventListener("click", function(){
    isLogin = !isLogin;
    updateAuthUI();
});

updateAuthUI();

document.getElementById("authBtn").addEventListener("click", function(){
    let user = document.getElementById("authUser").value.trim();
    let pass = document.getElementById("authPass").value.trim();

    if(!user || !pass){
        alert("Por favor completa todos los campos");
        return;
    }

    let users = JSON.parse(localStorage.getItem("users")) || [];

    if(isLogin){
        let foundUser = users.find(u => u.user === user && u.pass === pass);
        if(foundUser){
            localStorage.setItem("loggedIn", "true");
            localStorage.setItem("currentUser", user);

            if(user === "alecasango21@gmail.com" && pass === "AlejoC2006"){
                window.location.href = "panel_admin.html";
            } else {
                window.location.href = "panel_cliente.html";
            }
        } else {
            alert("Usuario o contraseña incorrectos");
        }
    } else {
        if(users.find(u => u.user === user)){
            alert("Este usuario ya está registrado");
            return;
        }
        users.push({user: user, pass: pass, saldo: 0});
        localStorage.setItem("users", JSON.stringify(users));
        alert("Cuenta creada con éxito. Ahora inicia sesión.");
        isLogin = true;
        updateAuthUI();
        document.getElementById("authUser").value = "";
        document.getElementById("authPass").value = "";
    }
});
</script>

</body>
</html>
