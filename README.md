# RSA Factoring Challenge

## Background Context

Before you continue reading, start this song in the background: [song link](song_link_here)

We have sniffed an unsecured network and found numbers that are used to encrypt very important documents. It seems that those numbers are not always generated using large enough prime numbers. Your mission, should you choose to accept it, is to factorize these numbers as fast as possible before the target fixes this bug on their server - so that we can decode the encrypted documents.

This project is NOT mandatory at all. It is 100% optional. Doing any part of this project will add a project grade of over 100% to your average. Your score won’t get hurt if you don’t do it, but if your current average is greater than your score on this project, your average might go down. Have fun!

## Requirements

### General

- You can choose the language of your choice.
- The OS needs to be Standard Ubuntu 20.04 LTS.

### Tasks

**Factorize all the things!**

- **Advanced**
- Factorize as many numbers as possible into a product of two smaller numbers.
- Usage: `factors <file>`
  - `<file>` is a file containing natural numbers to factor.
  - One number per line.
  - You can assume that all lines will be valid natural numbers greater than 1.
  - You can assume that there will be no empty line, and no space before and after the valid number.
  - The file will always end with a new line.
- Output format: `n=p*q` (one factorization per line).
  - `p` and `q` don’t have to be prime numbers.
- You can work on the numbers of the file in the order of your choice.
- Your program should run without any dependency: You will not be able to install anything on the machine we will run your program on.
- Time limit: Your program will be killed after 5 seconds if it hasn’t finished.
- Push all your scripts, source code, etc., to your repository.
- We will only run your executable `factors`.

**RSA Factoring Challenge**

- **Advanced**
- RSA Laboratories states that for each RSA number `n`, there exist prime numbers `p` and `q` such that `n = p × q`. The problem is to find these two primes, given only `n`.
- This task is the same as task 0, except:
  - `p` and `q` are always prime numbers.
  - There is only one number in the files.
- How far can you go in less than 5 seconds?

## Resources

Read or watch:

- RSA
- How does HTTPS provide security?
- Prime Factorization
- Why RSA?

## Repository

GitHub repository: [RSA-Factoring-Challenge](https://github.com/mugambi12/RSA-Factoring-Challenge)

### File: `factors`

- This file contains the code/script to factorize the numbers as described in Task 0.

### File: `rsa`

- This file contains the code/script to solve the RSA Factoring Challenge as described in Task 1.

## Usage

Here are some examples to help you understand the expected input and output:

