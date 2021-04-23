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