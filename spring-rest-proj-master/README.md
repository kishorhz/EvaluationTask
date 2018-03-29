Steps to run the project in eclipse

1. clone this project 
git clone https://github.com/rakeshpriyad/spring-rest-proj.git

import the project in eclipse


create a database and table using following command in mysql:

using following command

CREATE DATABASE /*!32312 IF NOT EXISTS*/`spring-mvc` /*!40100 DEFAULT CHARACTER SET latin1 */;

USE `spring-mvc`;

/*Table structure for table `number` */

DROP TABLE IF EXISTS `number`;

CREATE TABLE `number` (
  `id` bigint(20) NOT NULL AUTO_INCREMENT,
  `counter` bigint(20) DEFAULT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=2 DEFAULT CHARSET=latin1;

/*Data for the table `number` */

insert  into `number`(`id`,`counter`) values (1,0);


Run the project by right click on project Run on Server

