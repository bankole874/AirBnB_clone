# 0x00. AirBnB clone - The console

## What to learn
The AirBnB clone project starts now until… the end of the first year. The goal of the project is to deploy on your server a simple copy of the [AirBnB website](https://intranet.alxswe.com/rltoken/m8g02HcD2ovrl_K-zulYBw).

You won’t implement all the features, only some of them to cover all fundamental concepts of the higher level programming track.

After 4 months, you will have a complete web application composed by:
A command interpreter to manipulate data without a visual interface, like in a Shell (perfect for development and debugging)
A website (the front-end) that shows the final product to everybody: static and dynamic
A database or files that store data (data = objects)
An API that provides a communication interface between the front-end and your data (retrieve, create, delete, update them).

## Final Product

![App Screenshot](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/fe2e3e7701dec72ce612472dab9bb55fe0e9f6d4.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230508%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230508T111205Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=5e8a11f15025416e24ad6c4939ff1879caf6b0b3fa7339a94469ec7abc8968ef)

![App Screenshot](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/da2584da58f1d99a72f0a4d8d22c1e485468f941.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230508%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230508T111205Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=e984d05222bb20bdcd9b8d1be22d5bed2d2de1c686f267367cfdefac15920d23)

## Command Line interpreter

The console
- create your data model
- manage (create, update, destroy, etc) objects via a console / command interpreter
- store and persist objects to a file (JSON file)

The first piece is to manipulate a powerful storage system. This storage engine will give us an abstraction between “My object” and “How they are stored and persisted”. This means: from your console code (the command interpreter itself) and from the front-end and RestAPI you will build later, you won’t have to pay attention (take care) of how your objects are stored.

This abstraction will also allow you to change the type of storage easily without updating all of your codebase.

The console will be a tool to validate this storage engine.


## Tech Stack

**Client:** Group project, Python, OOP

**Server:** Ubuntu 20.0.4
