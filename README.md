vale
====
ï»¿-- phpMyAdmin SQL Dump
-- version 4.0.4
-- http://www.phpmyadmin.net
--
-- Servidor: localhost
-- Tiempo de generaciÃ³n: 26-11-2014 a las 06:31:42
-- VersiÃ³n del servidor: 5.6.12-log
-- VersiÃ³n de PHP: 5.4.12

SET SQL_MODE = "NO_AUTO_VALUE_ON_ZERO";
SET time_zone = "+00:00";


/*!40101 SET @OLD_CHARACTER_SET_CLIENT=@@CHARACTER_SET_CLIENT */;
/*!40101 SET @OLD_CHARACTER_SET_RESULTS=@@CHARACTER_SET_RESULTS */;
/*!40101 SET @OLD_COLLATION_CONNECTION=@@COLLATION_CONNECTION */;
/*!40101 SET NAMES utf8 */;

--
-- Base de datos: `basefindme`
--
CREATE DATABASE IF NOT EXISTS `basefindme` DEFAULT CHARACTER SET utf8mb4 COLLATE utf8mb4_spanish_ci;
USE `basefindme`;

-- --------------------------------------------------------

--
-- Estructura de tabla para la tabla `tabladatoscontacto`
--

CREATE TABLE IF NOT EXISTS `tabladatoscontacto` (
  `DatosContactoPersonasNumero` int(70) NOT NULL,
  `DatosContactoTelefono` int(10) NOT NULL,
  PRIMARY KEY (`DatosContactoPersonasNumero`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8 COLLATE=utf8_spanish_ci;

--
-- Volcado de datos para la tabla `tabladatoscontacto`
--

INSERT INTO `tabladatoscontacto` (`DatosContactoPersonasNumero`, `DatosContactoTelefono`) VALUES
(1, 1800335486),
(2, 1800335486),
(3, 1800335486),
(4, 1800335486),
(5, 1800335486),
(6, 1800335486),
(7, 1800335486),
(8, 1800335486),
(9, 1800335486),
(10, 1800335486),
(11, 1800335486),
(12, 1800335486),
(13, 1800335486),
(14, 1800335486),
(15, 1800335486),
(16, 1800335486),
(17, 1800335486),
(18, 1800335486),
(19, 1800335486),
(20, 1800335486),
(21, 1800335486),
(22, 1800335486),
(23, 1800335486),
(24, 1800335486),
(25, 1800335486),
(26, 1800335486),
(27, 1800335486),
(28, 1800335486),
(29, 1800335486),
(30, 1800335486),
(31, 1800335486),
(32, 1800335486),
(33, 1800335486),
(34, 1800335486),
(35, 1800335486),
(36, 1800335486),
(37, 1800335486),
(38, 1800335486),
(39, 1800335486),
(40, 1800335486),
(41, 2147483647),
(42, 1800335486),
(43, 1800335486),
(44, 1800335486),
(45, 1800335486),
(46, 1800335486),
(47, 1800335486),
(48, 1800335486),
(49, 979864144),
(50, 992962769);

-- --------------------------------------------------------

--
-- Estructura de tabla para la tabla `tabladatoslugar`
--

CREATE TABLE IF NOT EXISTS `tabladatoslugar` (
  `DatosLugarPersonaNumero` int(70) NOT NULL,
  `DatosLugarProvincia` text COLLATE utf8_spanish_ci NOT NULL,
  `DatosLugarCiudad` text COLLATE utf8_spanish_ci NOT NULL,
  `DatosLugarFecha` date NOT NULL,
  PRIMARY KEY (`DatosLugarPersonaNumero`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8 COLLATE=utf8_spanish_ci;

--
-- Volcado de datos para la tabla `tabladatoslugar`
--

INSERT INTO `tabladatoslugar` (`DatosLugarPersonaNumero`, `DatosLugarProvincia`, `DatosLugarCiudad`, `DatosLugarFecha`) VALUES
(1, 'Pichincha', 'Quito', '2013-11-18'),
(2, 'Tungurahua ', 'Ambato', '2010-12-12'),
(3, 'Tungurahua', 'Ambato', '2010-12-04'),
(4, 'Pichincha', 'Quito', '2010-08-10'),
(5, 'Pichincha', 'Quito', '2012-12-05'),
(6, 'pichincha', 'Quito', '2011-07-29'),
(7, 'Pichinca', 'Quito', '2004-06-10'),
(8, 'Tungurahua', 'Ambato', '2009-09-17'),
(9, 'Manabi', 'Manta', '2011-11-11'),
(10, 'Pichincha', 'Quito', '2012-06-17'),
(11, 'Pichincha', 'Quito', '2010-01-15'),
(12, 'Pichincha', 'Quito', '2012-04-28'),
(13, 'Pichincha', 'Quito', '2013-03-16'),
(14, 'Pichincha', 'Quito', '2012-09-08'),
(15, 'Loja', 'Loja', '2011-11-03'),
(16, 'Pichincha', 'Quito', '2008-10-04'),
(17, 'Pichincha', 'Quito', '2007-05-11'),
(18, 'Pichincha', 'Quito', '2012-07-07'),
(19, 'Guayas', 'Guayaquil', '2014-04-04'),
(20, 'Pichincha', 'Quito', '2014-11-10'),
(21, 'Pichincha', 'Quito', '2014-11-10'),
(22, '', '', '2014-11-07'),
(23, 'Pichincha ', 'Quito', '2014-11-08'),
(24, 'Guayas', 'Guayaquil', '2014-02-11'),
(25, 'Pichincha', 'Quito', '2014-10-05'),
(26, 'Pichincha', 'Quito', '2014-07-05'),
(27, 'Pichincha', 'Quito', '2014-11-03'),
(28, 'Pichincha ', 'Quito', '2014-10-31'),
(29, 'Pichincha', 'Quito', '2014-10-27'),
(30, 'Pichincha', 'Quito', '2014-10-24'),
(31, 'Pichincha', 'Quito', '2014-09-06'),
(32, 'manabi', 'Mnata', '2014-12-01'),
(33, 'Morona Santiago', 'Macas', '2012-10-14'),
(34, 'Chimborazo', 'Riobamba', '2014-01-28'),
(35, 'Pichincha', 'Quito', '2014-09-27'),
(36, 'Chimborazo', 'Riobamba', '2013-12-22'),
(37, 'Chimborazo', 'Riobamba', '2012-03-01'),
(38, 'Chimborazo', 'Riobamba', '2014-08-24'),
(39, 'Carchi', 'Tulcan', '2014-02-28'),
(40, 'pichincha ', 'quito', '0000-00-00'),
(41, 'Santa Elena', 'Salinas', '2014-04-11'),
(42, 'Guayas ', 'Guayaquil', '2014-08-20'),
(43, 'pichincha', 'Quito', '2014-05-18'),
(44, 'Pichincha ', 'Quito', '2014-04-21'),
(45, 'Tungurahua', 'Ambato', '2014-08-01'),
(46, 'Pichincha', 'Quito', '2014-08-01'),
(47, 'Guayas', 'Guayaquil', '2012-11-26'),
(48, 'loja', 'Loja', '2014-01-22'),
(49, 'Pichincha', 'Quito', '2013-12-13'),
(50, 'Pichincha', 'Quito', '2014-07-31');

-- --------------------------------------------------------

--
-- Estructura de tabla para la tabla `tabladatospersona`
--

CREATE TABLE IF NOT EXISTS `tabladatospersona` (
  `DatosPersonaNumero` int(70) NOT NULL,
  `DatosPersonaFoto` varchar(120) COLLATE utf8_spanish_ci NOT NULL,
  `DatosPersonaNombres` text COLLATE utf8_spanish_ci NOT NULL,
  `DatosPersonaApellidos` text COLLATE utf8_spanish_ci NOT NULL,
  `DatosPersonaEdad` int(3) DEFAULT NULL,
  `DatosPersonaGenero` text CHARACTER SET utf8mb4 COLLATE utf8mb4_spanish_ci NOT NULL,
  PRIMARY KEY (`DatosPersonaNumero`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8 COLLATE=utf8_spanish_ci;

--
-- Volcado de datos para la tabla `tabladatospersona`
--

INSERT INTO `tabladatospersona` (`DatosPersonaNumero`, `DatosPersonaFoto`, `DatosPersonaNombres`, `DatosPersonaApellidos`, `DatosPersonaEdad`, `DatosPersonaGenero`) VALUES
(1, '', 'Cesar Gustavo', 'Garzon Guaman', 33, 'Masculino'),
(2, '', 'Andres Fernando', 'Lopez Lisano', 24, 'Masculino'),
(3, '', 'Giovanna Paulina ', 'Perez Constante', 19, 'Femenino'),
(4, '', 'Jose Daniel', 'Guanuche Jaramillo', 23, 'Masculino'),
(5, '', 'Jose Luis', 'Valencia Ruiz', 21, 'Masculino'),
(6, '', 'Leonor Maria ', 'Ramirez Lopez', 75, 'Femenino'),
(7, '', 'Patricia Alexandra', 'SanguÃ±a Palacios', 20, 'Femenino'),
(8, '', 'Viviana Patricia', 'Yanza Freire', 25, 'Femenino'),
(9, '', 'Sergio Roniel', 'Zambrano Moreira', 26, 'Masculino'),
(10, '', 'Camilo Carlos ', 'Tobar Abril', 51, 'Masculino'),
(11, '', 'Maria Fernanda ', 'Guerrero Mejia', 25, 'Femenino'),
(12, '', 'Estefania Carolina ', 'Garzon Ardila', 22, 'Femenino'),
(13, '', 'Santiago David ', 'Romo Cordova', 24, 'Masculino'),
(14, '', 'Oscar Bladimir', 'Suarez Shiguango', 20, 'Masculino'),
(15, '', 'Telmo Orlando', 'Pacheco Aguilar', 33, 'Masculino'),
(16, '', 'Luis Daniel', 'Sigcho Nacato', 33, 'Masculino'),
(17, '', 'Enrique Aurelio', 'Witt Baquero', 52, 'Masculino'),
(18, '', 'Juliana Lizbeth', 'Campoverde Rodriguez', 19, 'Femenino'),
(19, '', 'Cristian Jhon', 'Aldaz Morocho', 16, 'Masculino'),
(20, '', 'Jenifer', 'Garcia Quintana', 13, 'Femenino'),
(21, '', 'Segundo', 'Ruiz', 80, 'Masculino'),
(22, '', 'Marillyn Jessenia', 'Quispe Guachamin', 15, 'Femenino'),
(23, '', 'Mayuri Priscila', 'Arequipa Altamirano', 7, 'Femenino'),
(24, '', 'Cesar Augusto ', 'Escobar Paez', 73, 'Masculino'),
(25, '', 'Noe', 'Panta', 10, 'Masculino'),
(26, '', 'Guillermo Paul ', 'Flores Guaman', 26, 'Masculino'),
(27, '', 'Jorge Luis ', 'Arevalo Reyes', 20, 'Masculino'),
(28, '', 'Eddy Javier', 'Castro PatiÃ±o', 29, 'MAsculino'),
(29, '', 'Andres ', 'Valencia', 19, 'Masculino'),
(30, '', 'Andrea', 'Justin', 15, 'Femenino'),
(31, '', 'Maximino Jacobo', 'Garcia Moreira', 80, 'Masculino'),
(32, '', 'Aurelio ', 'Mero Dominguez', 0, 'Masculino'),
(33, '', 'Jessica Virginia ', 'Cueva Granda', 0, 'Femenino'),
(34, '', 'Angie Marianella', 'Carrion Labanda', 0, 'Femenino'),
(35, '', 'Jose', 'Brones Basurto', 0, 'Masculine'),
(36, '', 'Thalia Sarahi', 'Altamirano Cajilema', 0, 'Femenino'),
(37, '', 'Luz America', 'Armas Orozco', 0, 'Femenino'),
(38, '', 'Patricia Elizabeth', 'Toca Calderon', 0, 'Femenino'),
(39, '', 'Luis jenberson', 'Lopez Paz', NULL, 'Masculino'),
(40, '', 'Jose ', 'Albarado Yaselga', 0, 'Masculino'),
(41, '', 'Marco', 'Santelices Rivera', NULL, 'Masculino'),
(42, '', 'Manuel Alberto ', 'Cedeno Zambrano', NULL, 'Masculino'),
(43, '', 'Corazon de Jesus', 'Diaz Espinosa', NULL, 'Masculino'),
(44, '', 'Christia AntoÃ±o', 'Acevedo Oralan', NULL, ''),
(45, '', 'Nelly de Jesus', 'Oviedo Valdez', NULL, 'Femenino'),
(46, '', 'Alex David', 'Sisalema Ontaneda', NULL, 'Masculino'),
(47, '', 'Ivan Alfredo', 'Jiminez Flores', NULL, 'Masculino'),
(48, '', 'Maria del Rocio', 'Conde Guaman', NULL, ''),
(49, '', 'Ernesto Gustavo', 'Braga Imbaquigo', 68, 'Masculino'),
(50, '', 'Gabriel ', 'Albuja', 90, 'Masculino');

--
-- Restricciones para tablas volcadas
--

--
-- Filtros para la tabla `tabladatoscontacto`
--
ALTER TABLE `tabladatoscontacto`
  ADD CONSTRAINT `tabladatoscontacto_ibfk_1` FOREIGN KEY (`DatosContactoPersonasNumero`) REFERENCES `tabladatospersona` (`DatosPersonaNumero`) ON DELETE CASCADE ON UPDATE CASCADE;

--
-- Filtros para la tabla `tabladatoslugar`
--
ALTER TABLE `tabladatoslugar`
  ADD CONSTRAINT `tabladatoslugar_ibfk_1` FOREIGN KEY (`DatosLugarPersonaNumero`) REFERENCES `tabladatospersona` (`DatosPersonaNumero`) ON DELETE CASCADE ON UPDATE CASCADE;

/*!40101 SET CHARACTER_SET_CLIENT=@OLD_CHARACTER_SET_CLIENT */;
/*!40101 SET CHARACTER_SET_RESULTS=@OLD_CHARACTER_SET_RESULTS */;
/*!40101 SET COLLATION_CONNECTION=@OLD_COLLATION_CONNECTION */;

