# <span style="color:Orange"> JavaScript Practical Question </span>

### <span style="color:pink"> Q1 : How to get first n elements in an array ? </span>

    const data = () => {
        let x = [1,2,3,4,5,6,7,8,9]
        console.log(x.splice(0,5))   # Output = [1,2,3,4,5]
    }

    data()

### <span style="color:#845ec2"> Q2 : How to check if an array includes a value in javascript ? </span>

    const data = () => {
        let x = [1,2,3,4,5,6,7,8]
        console.log(data.includes(9)) #False
        console.log(data.includes(2)) #True
    }

    data()


### <span style="color:#00ff7f">Q3 : How to remove a property from javascript object ?</span>

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

### <span style="color:#5bc0de"> Q4 : How to find length of a javascript object ? </span>

    const data = () => {
        let Obj2 = {
            id = 1,
            name = "foo",
            value = 'bar',
        }
        return Object.keys(Obj2).length
    }

    console.log(data())

### <span style="color:#cdb071"> Q5 : How to merge properties of two objects dynamically in javascript ? </span>

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

### <span style="color:#a178df"> Q6 : How to Check whether a string contains a substring or not in javascript ? </span>

    const checkString = () => {
        let a = "FooBar"
        console.log(a.includes(oo)) #True
        console.log(a.includes(xy)) #False
    }
    checkString()

### <span style="color:#ff8066"> Q7 : How to Remove a specific item from an array ? </span>

    const Remove = () => {
        let A1 = [1,2,3,4,5,6,7,8]
        let remove = A1.filter(x=> x !== 1) 1 removed from the array
        console.log(remove) # [2,3,4,5,6,7,8]
        }
    Remove()

### <span style="color:#bbf1fa"> Q8 : How to get Current URL using Javascript? </span>

    const getUrl = () => {
        return window.location.href
    }
    console.log(getUrl())

### <span style="color:#ffe9d2"> Q9 : How to insert item in an array at specific index in javascript ? </span>

    const insertItem = () => {
        let arr = [1,2,3,4,5,6,7,8,9]
        arr.splice(0,1,0) #insert at index 0 = 0
        console.log(arr)
    }
    insertItem()

### <span style="color:#8e6a4c">Q10 : How to loop through an object in javascript. </span>

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

### <span style="color:#fe5564"> Q11 : How to replace all the occurrences of a string in javascript ? </span>

    const replaceString = () => {
        let string = "FooBar"
        let newString = string.replaceAll('F','T')

        console.log(newString)
    }
    replaceString()

### <span style="color:#bc6ff1"> Q12 : How to round to two decimal value in javascript ? </span>

    const roundOff = () => {
        
        let a = 2.788
        let b = Math.round(a)
        console.log(b)
    }
    roundOff()

### <span style="color:#fecd1a"> Q13 : How to check if object is an array in javascript ?

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

### <span style="color:#278efc"> Q14: How to Find object and index of object based on id in an array in javascript ? </span>

    const foo = () => {

        let a = [{id:1, name: 'foo'}, {id:2, name: 'bar'}]

        console.log(x.find(data => data.id === 2))
        console.log(x.findIndex(data => data.id === 2))
    }
    foo()

### <span style="color:#6ef2d3">Q15: How to return unique values from an array in javascript ?

    const unique = () => {
        let x = [1,2,3,3,4,4,5,'a','a','b']

        console.log(...new Set(x))
    }
    unique()

### <span style="color:#f8a5ff"> Q16: How to Open url in new tab in javascript ? </span>

    const newTab = () => {
        window.open('https://github/AliZaiN-157/')
    }

    newTab()


### <span style="color:#e2e7eb"> Q17: How to Check if property exists in an object in javascript ? </span>

    const Check = () => {

        let obj = {
            id: 1,
            name: 'foo',
        }
    console.log('key' in obj) #false
    console.log('name' in obj) #true
    }
