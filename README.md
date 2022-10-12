<h1 align="center">Teaching Staff Data Management System using JPA</h1>

<p align="center">
  This is a data management System for teaching staff using JPA. Following tutorial from [Tutorialspoint].
</p>

<p>Inheritance is the core concept of object oriented language, therefore we can use inheritance relationships or strategies between entities. JPA support three types of inheritance strategies such as SINGLE_TABLE, JOINED_TABLE, and TABLE_PER_CONCRETE_CLASS.</p>


<p>Let us consider an example of Staff, TeachingStaff, NonTeachingStaff classes and their relationships as follows:</p>

![inheritance_strategy](https://user-images.githubusercontent.com/6496751/195464291-d71682af-2300-4fe5-bc38-9c76497c7c56.png)

<p>In the above shown diagram Staff is an entity and TeachingStaff and NonTeachingStaff are the sub entities of Staff. Here we will discuss the above example in all three strategies of inheritance.</p>

<h3>Single Table strategy</h2>
<p>Single-Table strategy takes all classes fields (both super and sub classes) and map them down into a single table known as SINGLE_TABLE strategy. Here discriminator value plays key role in differentiating the values of three entities in one table.</p>
