# cold-store-management
--json output

[
    coldStore:{
        farmers:{
            id:"",
            personalDetails:{
                name:"",
                father's Name:"",
                address:{
                    village:"",
                    district:"",
                    landmark:""
                },
                contactDetails:{
                    contactNumber:"",
                    altContactNumber:""
                },
            },
            cropDetails:{
                dateDeposited:[
                    {
                        variety:""
                        amount:" pkts",
                        lotNumber:"",
                        floorNumber:"",
                        vehicleType:"",
                        vehicleNumber:"",
                        pickedDate:"",
                        LabourCharge:"",
                        DropCharge:"",
                        BardanaCharge:"",
                        totalAmount:""
                    },
                ],
                cropRentRate:"",
                DropRate:"",
                SackRate:"",
            },
            balancesheet:{
                amountCredited:{
                    crDate:"",
                    amount:"",
                },
                amountDebited:{
                    dbDate:"",
                    amount:"",
                },
                balanceAmount:"",
                clearStatus:
            }
        },
        staff:{
            id:"",
            position:"",
            personalDetails:{
                name:"",
                address:{
                    village:"",
                    district:"",
                    landmark:"",
                }
                contactDetails:""
            },
            balancesheet:{
                amountCredited:{
                    crDate:"",
                    amount:"",
                },
                amountDebited:{
                    dbDate:"",
                    amount:"",
                },
                salaryAmount:"",
                balanceAmount:""
            }
        },
        structure:{
            lotNumber:"",
            floorNumber:"",
        },
        machines:{
            generators:[{
                brand:"",
                model:"",
                price:"",
                shopPurchased:{
                    name:"",
                    contactNumber:"",
                    address:"",
                    personIncharge:""
                }
                purchaseDate:"",
                ServiceDueDate:""
            },{}],
            coolingTower:{
                brand:"",
                model:"",
                price:"",
                shopPurchased:{
                    name:"",
                    contactNumber:"",
                    address:"",
                    personIncharge:""
                }
                purchaseDate:"",
                ServiceDueDate:""
            },
            ammoniaTank:{
                brand:"",
                model:"",
                price:"",
                shopPurchased:{
                    name:"",
                    contactNumber:"",
                    address:"",
                    personIncharge:""
                }
                purchaseDate:"",
                ServiceDueDate:""
            }
        },
        merchant:{
            id:"",
            personalDetails:{
                name:"",
                address:{
                    village:"",
                    district:"",
                    landmark:""
                },
                contactDetails:[

                ]
            },
            cropDetails:{
                dateDeposited:[
                    {
                        variety:""
                        amount:" pkts",
                        lotNumber:"",
                        pickedDate:"",
                    }
                ],
                cropRate:"",
                DropRate:"",
                SackRate:"",
            },
            balancesheet:{
                amountCredited:{
                    crDate:"",
                    amount:"",
                },
                amountDebited:{
                    dbDate:"",
                    amount:"",
                },
                balanceAmount:"",
                clearStatus:
            }
        },
        balancesheet:{
                amountCredited:{
                    crDate:"",
                    amount:"",
                    purpose:""
                },
                amountDebited:{
                    dbDate:"",
                    amount:"",
                    purpose:""
                },
                balanceAmount:""
            }
    }
]




Setup Procedure:

1.set up a mongodb.
2.load the database file.
3.install nodejs
4.{npm install} to install the dependencies.
5.run the shell script file.

task FollowUp:
stack used:MEAN
1.db design for the mongo as well the relational   mySql database.(ref:json indicated below)
2.home screen (angular)
    a. top logo
    b. deposit season
    c. withdrawl reason
    d. General Inquiry
    e. Daily expense update
    f. Add a new member
3.Deposit Season(angular)
    a. Aamat register
    b. Daily report
4.Withdrawl Season(angular)
    a. 
5.General Inquiry:
    a.category
    b.filter
    c.data
    d.status
    e.result
6.Daily expense update
    a. print expense update
    b. update expense form
7.Add a new member
    a. type of member
    b. update details
