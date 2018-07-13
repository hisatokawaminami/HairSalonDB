# Epicodus Week8 Project C# Hair Salon DB

## Created

07/13/2018

## About

Create a program that shows a list of stylists and their clients. A user is able to add stylists and clients to the database

## Spec

|Behavior|	Input|Output	|Justification|
|:--------|:-------------:|:--------------:|:---:|:---:|
|adds names of stylists| Yoko Bono| Yoko Bono|saves the input into DB
|adds name of clients | Jon Lemon | Jon Lemon|saves the input to the DB

## Technology Used

C#, .NET Core 1.1, mySQL

## Installation

Clone from:
https://github.com/hisatokawaminami/HairSalonDB.git

Re-create the databases with terminal:
- CREATE DATABASE hair_salon;
- USE hair_salon;
- CREATE TABLE stylists (id serial PRIMARY KEY, name VARCHAR(255));
- CREATE TABLE clients (id serial PRIMARY KEY, name VARCHAR(255));

## Credits
Hisato Kawaminami


## License

The MIT License (MIT)

Copyright (c) 2015 Hisato Kawaminami

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
