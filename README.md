## JavaScript Practical Question

<br />
<br />

Q1 : How to get first n elements in an array ?

    const data = () => {
        let x = [1,2,3,4,5,6,7,8,9]
        console.log(x.splice(0,5))   # Output = [1,2,3,4,5]
    }

    data()

Q2 : How to check if an array includes a value in javascript ?

    const data = () => {
        let x = [1,2,3,4,5,6,7,8]
        console.log(data.includes(9)) #False
        console.log(data.includes(2)) #True
    }

    data()


Q3 : How to remove a property from javascript object ?

    const Property = () => {
        let Obj1 = {
            id = 1,
            name = "foo",
            value = 'bar',
        }
        delete Obj1.id
        delete Obj1["id"]
    }

    Property()

Q4 : How to find length of a javascript object ?

    const data = () => {
        let Obj2 = {
            id = 1,
            name = "foo",
            value = 'bar',
        }
        return Object.keys(Obj2).length
    }

    console.log(data())

Q5 : How to merge properties of two objects dynamically in javascript ?

        const mergeProp = () => {
            let x = {
                id:1,
                name: 'foo'
            }
            let y = {
                p1 = "property1"
                p2 = "property2"
            }
            let z = {...x,...y}
            console.log(z) 
        }
        mergeProp()

Q6 : How to Check whether a string contains a substring or not in javascript ?

    const checkString = () => {
        let a = "FooBar"
        console.log(a.includes(oo)) #True
        console.log(a.includes(xy)) #False
    }
    checkString()

Q7 : How to Remove a specific item from an array ?

    const Remove = () => {
        let A1 = [1,2,3,4,5,6,7,8]
        let remove = A1.filter(x=> x !== 1) 1 removed from the array
        console.log(remove) # [2,3,4,5,6,7,8]
        }
    Remove()

Q8 : How to get Current URL using Javascript?

    const getUrl = () => {
        return window.location.href
    }
    console.log(getUrl())

Q9 : How to insert item in an array at specific index in javascript?

    const insertItem = () => {
        let arr = [1,2,3,4,5,6,7,8,9]
        arr.splice(0,1,0) #insert at index 0 = 0
        console.log(arr)
    }
    insertItem()

Q10 : How to loop through an object in javascript.

    const Loop = () => {
        let obj = {
            id : 1,
            name: 'foo',
        }

        for(let i of Object.keys(obj)) {
            console.log(`${i} = ${obj[i]}`)
        }
    }
    Loop()

Q11 : How to replace all the occurrences of a string in javascript ?

    const replaceString = () => {
        let string = "FooBar"

        let newString = string.replaceAll('F','T')

        console.log(newString)
    }
    replaceString()

Q12 : How to round to two decimal value in javascript ?

    const roundOff = () => {
        
        let a = 2.788
        
        let b = Math.round(a)

        console.log(b)
    }
    roundOff()

Q13 : How to check if object is an array in javascript ?

    const checkObject = () => {

        let r = {
            id : 1,
        }

        console.log(Array.isArray(r)) #False

        let s = [{
            id : 1,
        }]

        console.log(Array.isArray(s)) #True
    }

    checkObject()