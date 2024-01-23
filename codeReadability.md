### How to Structure Your Code for Readability

return the length of a string
`function getLength(str){
    if(typeof str === 'string'){
        return str.length();
    }  
    throw new Error('parameter must be a string');
}`

more <b>refined</b> approach
`function getLength(str){
    if(typeof str !== 'string'){
        throw new Error('parameter must be a string');
    }
    return str.length();
} `

Can change nested structure to more refined

`function foo(){
    if(<!-- condition A -->){
        if(<!-- condition B -->){
            if(<!-- condition C -->){
                <!-- Handle condtion C -->
            }
            <!-- Handle Condition B -->
        }
        <!-- Handle Condition A -->
    }
}`

into this:

` function foo(){
    if(<!-- condition A -->){
         <!-- Handle Condition A -->
    }
    if(<!-- condition B -->){
        <!-- Handle Condition B -->
    }
    if(<!-- condition C -->){
        <!-- Handle condtion C -->
    }
}
`
