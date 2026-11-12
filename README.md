# React-Lab-Exercise-2-Using-Props-Step-by-Step

## Name : Moulishwar G
## Register Number : 2305001020

# Aim
To create a React application that demonstrates how to pass data from a parent component to a child component using Props.

# Program:

## i) App.jsx
```python
 
  import Student from "./Student"; 
import "./index.css"; 
function App() { 
 return ( 
 <div> 
 <h1>Student Information</h1> 
 <Student 
 name="Moulish" 
 id="2305001020" 
 department="CSE" 
 year="III Year" 
 /> 
 <Student 
 name="Kishore" 
 id="2305001021" 
 department="IT" 
 year="II Year" 
 /> 
 <Student 
 name="Hari" 
 id="2305001022" 
 department="AIDS" 
 year="IV Year" 
 /> 
 </div> 
 ); 
} 
export default App

```

# Output:

<img width="810" height="397" alt="image" src="https://github.com/user-attachments/assets/cdb1daeb-3743-4511-8988-f970db12fdce" />


