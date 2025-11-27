<h1>Pasos a seguir</h1>
<section>
  <h2>1. Fork</h2>
  <p>Arriba a la derecha hacé clic en: Fork 
    <br>En Dueño (Owner), ingresa el nombre de usuario de tu cuenta de GitHub (Ejemplo: Juan1234).
    <br>En Nombre del Repositorio (Repository Name), te figurara por defecto ClaseGit. Dejalo asi.
  </p>
  <p>GitHub va a crear tu copia del repositorio en tu cuenta.</p>
  <code>https://github.com/"tuCuenta"/ClaseGit</code>
  <p>Ejemplo: <code>https://github.com/Juan1234/ClaseGit</code></p>
</section>
<section>
  <h2>2. Clonar el repositorio</h2>
  <p>Abrí la terminal, ubicáte en una carpeta de trabajo y escribí:</p>
  <code>git clone https://github.com/"tuCuenta"/ClaseGit.git</code><br>
  <p>Siguiendo el ejemplo anterior: <code>git clone https://github.com/Juan1234/ClaseGit</code></p>
  
  <p>Luego: </p>
  <code>cd ClaseGit</code>
  
</section>
<section>
  <h2>3. Crear una rama con tu nombre</h2>
  <code>git checkout -b tuNombre</code>
  <p>Ejemplo: <code>git checkout -b juan</code></p>
</section>
<section>
  <h2>4. Editar archivo</h2>
  <p>Abre el archivo participantes.txt con tu editor de preferencia y agregá tu nombre al final del archivo:<br><br>
  Lista de participantes:<br>
  - Cristian<br>
  - Nahuel<br>
  - Francisco<br>
  <strong>- Juan</strong><br><br>
  Guardar y cerrar.</p>
</section>
<section>
  <h2>5. Confirmar los cambios</h2>
  <code>git add participantes.txt</code><br>
  <code>git commit -m "Agrego mi nombre al archivo de participantes"</code>
</section>
<h2>6. Enviar la rama al repositorio remoto</h2>
<code>git push origin tuNombre</code>
<p>Si seguimos el ejemplo anterior: <code>git push origin juan</code></p>
<h2>️7. Crear un Pull Request</h2>
<ol>
 <li>Entrá a tu fork en GitHub: <code>https://github.com/"tuCuenta"/ClaseGit</code> </li>
 <li>Vas a ver un cartel amarillo, click en el boton verde que dice: <strong>“Compare & pull request”</strong></li>
 <li>Por defecto, estará el repositorio original como destino y el repositorio en tu cuenta como principal, para comparar los cambios de tu rama con la rama principal del repositorio original.</li>
  <li>Ya solo queda hacer click en Crear Pull Request.</li>
</ol>
<p>Tu cambio quedara propuesto para el reposiorio original.</p>





















