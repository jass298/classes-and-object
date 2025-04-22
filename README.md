
//classes and object

class RailWayForm {
    submit(){
        alert( this.name + this.age + "form submitted")
    }
    cancel(){
        alert("this form is canceled")
    }
    fillagain(){//we can make and fill object accordind to own choice
        alert("please check the form and fill again")
    }
    fill(givenName,givenage){

        this.name = givenName//print name
        this.age = givenage //will  print given age

        alert(this.name +  " the age of " + this.age + "has filled the form")
    }
}
console.log(RailWayForm)
//will create form for both person and others
let harry = new RailWayForm()
let rohan = new RailWayForm()
console.log(harry)
 
harry.submit()
rohan.submit()///for subbmiting 
rohan.cancel()//can cancel the form
harry.fillagain()
harry.fill("harry","21")

console.log(harry)
 
console.log(rohan)
