create schema studentmgnt;

CREATE TABLE  studentmgnt.student_details  (
CREATE TABLE  student_details  (
   student_id  int NOT NULL AUTO_INCREMENT,
   student_name  varchar(45) DEFAULT NULL,
   aadhar_card_number  varchar(45) DEFAULT NULL,
   parents_name  varchar(45) DEFAULT NULL,
   ph_number  varchar(45) DEFAULT NULL,
   class_name  varchar(45) DEFAULT NULL,
   section  varchar(45) DEFAULT NULL,
   fee_paid  varchar(45) DEFAULT 'not paid',
  PRIMARY KEY ( student_id )
) ;


CREATE TABLE studentmgnt.student_marks  (
   id  int NOT NULL AUTO_INCREMENT,
   student_id  int DEFAULT NULL,
@@ -22,4 +22,3 @@ CREATE TABLE studentmgnt.student_marks  (
   language  varchar(45) DEFAULT NULL,
  PRIMARY KEY ( id )
) ;

