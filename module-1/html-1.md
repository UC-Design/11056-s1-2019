# Module 1: HTML5 and CSS

##  HTML 1: Introduction to the Web

###  Introducion

An introduction to the Web

- How the Web works
- Domains and hosting
- Production process
- Key terms (HTML and CSS)

###  The internet and the Web

Used interchangeably but not the same thing

The Web is a protocol on the internet

Other protocols include:
- Email
- FTP (file transfer protocol)
- Peer-to-peer (torrent)
- Domain Name System (DNS)


###  How the Web works

User enters domain
Query goes to domain name system (DNS) server 
DNS server returns IP address 
IP address points to web host (server)
Web host returns actual website 





## Domains and Hosting





###  Domains

Easier to remember than a set of numbers

www.google.com

`www`: hostname
`google`: name
`com`: top level domain


###  Getting a domain

Anyone can get a domain, but you need to pay for it

**.com **  
- can be registered for a year or more
- often free with hosting

**.com.au**
- need to have an ABN to register

Many more types available



###  Hosting

You pay a company to rent some space on their server

They make sure their servers can:  
- handle traffic (bandwidth) 
- won’t go offline 

Depending on your requirements, hosting can be cheap or really expensive








# Key terms





###  HTML

- Hyper Text Markup Language
- Created by Tim Berners-Lee, first public version around 1991
- For content - headings, paragraphs, defining images
- Tags already exist - you can’t make them up

```
<p>This is a paragraph</p>
```



###  CSS

- Cascading Style Sheets
- For appearance. First version in 1996
- How to change colours, width, height etc:
```
p {  
    background-color: #99cc00;  
    font-size: 12px;  
}
```



###  Don't combine them!

- HTML and CSS are independent
- They should not be combined 
- So, no CSS inside a HTML document
- Don't use inline styles in your HTML:

```
    <p style="background-color: #99cc00; font-size:  12px;" >
        This is a paragraph
    </p>
    
```


## Production Process


###  Common production process

1. Design flat website
2. Build website ‘locally’ (on your own computer) 
3. Upload to development server and test
4. Fix any issues
5. Deploy website to the world



###  Suggested production process 

**Sketching in code methodology**

1. Sketch website design on paper
2. Start sketching in code
3. Build website ‘locally’ 
4. Test in browser, Validate code, Fix

A process of constant refinement.


            