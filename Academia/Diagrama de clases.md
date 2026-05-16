Diagrama de Clases
Diseñar el diagrama de clases del sistema de evaluación educativa.

Clases requeridas:

- Student
- Klass
- Grade
- Result
- Teacher
- User
- Quiz
- Question
- Essay
- Multiple Choice
- Answer
- Project
- Practice

Notas:

- “Klass” se utiliza en lugar de “Class” porque en muchos lenguajes de programación “Class” es una palabra reservada.
- Las clases deben estar correctamente organizadas mediante herencia, por ejemplo:
    - Teacher y Student heredan de User.  
- El sistema debe permitir asociaciones polimórficas para que una misma clase Answer pueda relacionarse con distintos tipos de preguntas.