Title: CTBD – Concepts and Technologies for Distributed Systems and Big Data Processing
CSS: styles.css

# CTBD

## Concepts and Technologies for Distributed Systems and Big Data Processing

The course provides an overview of recent advances in distributed systems for
Big Data processing. The course starts presenting computational models for high
throughput batch processing like MapReduce. Next, we will introduce software
engineering techniques for distributed systems such as REST and component-based
architectures. We will then cover low latency real time stream processing and
complex event processing. Finally, we will present advanced topics in
distributed data-intensive systems, such as geodistribution and security. The
course focuses both on the fundamental concepts as well as on the concrete
technologies and applications of the aforementioned techniques to real-world
case studies.

### Summer Term 2016

#### Forum

Please use the forum for your questions. Other students can benefit from the
answers to your questions and can help you, too. Answers will remain as a
reference for other people.

[Concepts and Technologies for Distributed Systems and Big Data Processing](https://www.fachschaft.informatik.tu-darmstadt.de/forum/viewforum.php?f=580)

#### Exam

<!--
<div class="info">
  The Exam will take place on 26th of July, 11:00–13:00 in S311/08.
</div>

<div class="info">
  <p>The Exam Review will take place on 29th of July, 9:00–11:00 in S202/A213.
  Please use the time slot assigned to your surname.</p>

  Surname starting with
  <table>
    <tr><td>A–F</td><td>9:00</td></tr>
    <tr><td>G–K</td><td>9:30</td></tr>
    <tr><td>L–R</td><td>10:00</td></tr>
    <tr><td>S–Z</td><td>10:30</td></tr>
  </table>

  <p>Since the grades will probably not be available in TUCaN before the Exam Review,
  we will provide the possibility to review the exam when the grades are also available in TUCaN.</p>

  <p>The Exam Review on 29th of July will take place as announced. You can learn you grade there.</p>
</div>

<div class="info">
  <p>A second Exam Review for everyone who did not have the chance to review the exam yet
  will take place on 30th of August, 10:00–12:00 in S202/A213.</p>

  <p>The grades are available in TUCaN now.</p>
</div>

<div class="info">
  We will offer an exam this winter term (WS 16/17) on 6th of March.
  Depending on the number of registrations, it will be an oral or a written exam.
</div>
-->

<div class="info">
  We will offer a written exam this winter term (WS 16/17) on 6th of March, 17:00–19:00 in S101/A1.
</div>

<div class="info">
  The Exam Review will take place on 17th of March, 14:00–15:00 in S202/A313.
</div>

#### Lectures

Lectures are held on Tuesdays, 9:50–11:30 in S202/C205.

* April 12  
  Course information, Motivation, Introduction to distributed systems  
  [Slides 1](CTBD_01_organization.pdf)  
  [Slides 2](CTBD_02_intro.pdf)  
  [Exercise 1](CTBD_ex01.pdf)
  
* April 19  
  [Slides 3](CTBD_03_bigdata_intro.pdf)  
  [Slides 4](CTBD_04_mapreduce.pdf)  
  [Exercise 2](CTBD_ex02.pdf) + [Code](CTBD_ex02.zip)  
  [Solution 2](CTBD_sol02.pdf) + [Code](CTBD_sol02.zip)  
  [MapReduce paper](http://research.google.com/archive/mapreduce.html) by Dean and Ghemawat
  
* April 26  
  [Slides 5](CTBD_05_mapreduce.pdf)  
  [Slides 6](CTBD_06_gfs-hdfs.pdf)  
  [Slides for Hadoop Demo](CTBD_05b_two_step_join.pdf) + [Code for multi-stage MapReduce](CTBD_05b_two_step_join.zip)  
  [Exercise 3](CTBD_ex03.pdf)  
  [Solution 3](CTBD_sol03.pdf)  
  [Google File System paper](http://research.google.com/archive/gfs.html) by Ghemawat et al.

* May 4 – **date and place changed  
  Wednesday, 11:40–13:20 in S101/A03**  
  [Slides 7](CTBD_07_cep.pdf)  
  [Exercise 4](CTBD_ex04.pdf) + [Code](CTBD_ex04.zip)  
  [Solution 4](CTBD_sol04.pdf) + [Code](CTBD_sol04.zip)

* May 10  
  [Slides 7](CTBD_07_cep.pdf) updated  
  no exercise this week

* May 17  
  [Slides 8](CTBD_08_concurrency.pdf) + [Slides 8 with notes](CTBD_08_concurrency_notes.pdf) \[updated\]  
  [Exercise 5](CTBD_ex05.pdf) + [Code](CTBD_ex05.zip)  
  [Solution 5](CTBD_sol05.pdf) + [Code](CTBD_sol05.zip)

* May 24  
  [Slides 9](CTBD_09_futures_actors.pdf) \[updated\]  
  [Exercise 6](CTBD_ex06.pdf)  
  [Solution 6](CTBD_sol06.pdf)

* May 31  
  [Slides 10](CTBD_10_components.pdf)  
  no exercise this week

* June 7  
  [Slides 11](CTBD_11_web_services.pdf)  
  [Exercise 7](CTBD_ex07.pdf)  
  [Solution 7](CTBD_sol07.pdf) + [Code](CTBD_sol07.zip)

* June 14  
  [Slides 12](CTBD_12_spark.pdf) \[updated\]  
  [Exercise 8](CTBD_ex08.pdf) + [Code](CTBD_ex08.zip)  
  [Solution 8](CTBD_sol08.pdf) + [Code](CTBD_sol08.zip)  
  [Apache Spark Resilient Distributed Datasets paper](http://www-bcf.usc.edu/~minlanyu/teach/csci599-fall12/papers/nsdi_spark.pdf) by Zaharia
et al.

* June 21  
  [Slides 13](CTBD_13_geo_distributed_big_data.pdf)  
  [Exercise 9](CTBD_ex09.pdf)

* June 28 – **slightly postponed to 10:00**  
  [Slides 14](CTBD_14_resource_management.pdf)  
  [Slides 15](CTBD_15_secure_big_data.pdf)  
  [Exercise 10](CTBD_ex10.pdf)

* July 5  
  guest lecture  
  [Slides I](20160630_Lecture_Darmstadt_Part1.pdf)  
  [Slides II](20160705_Lecture_Darmstadt_Part2.pdf)

* July 12  
  [Slides 16](CTBD_16_spark_streaming.pdf)  
  [Slides 17](CTBD_17_preparation.pdf)

* July 26  
  Exam


<small id="footer">based on minimal theme by [orderedlist](https://github.com/orderedlist)</small>
