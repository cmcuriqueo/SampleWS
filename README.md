# SampleWS
Web Service

###MySQL Databases
``` 
SET SQL_MODE = "NO_AUTO_VALUE_ON_ZERO";
SET time_zone = "+00:00";

--
-- Base de datos: `dbtest`
--
CREATE DATABASE IF NOT EXISTS `dbtest` DEFAULT CHARACTER SET latin1 COLLATE latin1_swedish_ci;
USE `dbtest`;

-- --------------------------------------------------------

--
-- Estructura de tabla para la tabla `people`
--

CREATE TABLE `people` (
  `id` int(10) NOT NULL,
  `name` varchar(32) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

--
-- Volcado de datos para la tabla `people`
--

INSERT INTO `people` (`id`, `name`) VALUES
(1, 'leonardo gado'),
(2, 'aitor tilla');

--
-- Índices para tablas volcadas
--

--
-- Indices de la tabla `people`
--
ALTER TABLE `people`
  ADD PRIMARY KEY (`id`);

--
-- AUTO_INCREMENT de las tablas volcadas
--

--
-- AUTO_INCREMENT de la tabla `people`
--
ALTER TABLE `people`
  MODIFY `id` int(10) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=3;

``` 
