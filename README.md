# Crudnode.js
Crud de prueba con conexion a Mysql para el curso nuevo de node.js de digital webdise
Pasos para ejecutar el proyecto

mkdir express-mysql-crud // ya se creo la carpeta
cd express-mysql-crud
npm init -y
npm install express mysql body-parser

-- Script para crear la tabla de estudiantes
CREATE TABLE estudiantes (
  id INT AUTO_INCREMENT PRIMARY KEY,
  nombre VARCHAR(255) NOT NULL,
  edad INT NOT NULL,
  curso VARCHAR(255) NOT NULL
);

-- Script para insertar datos iniciales en la tabla de estudiantes
INSERT INTO estudiantes (nombre, edad, curso) VALUES
  ('Estudiante 1', 20, 'Curso A'),
  ('Estudiante 2', 22, 'Curso B'),
  ('Estudiante 3', 21, 'Curso C');
