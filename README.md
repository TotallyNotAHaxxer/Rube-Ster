# Rube-Ster
a web recon framework built around ruby and rust 
    
    installs ==> 
    
    git clone https://github.com/ArkAngeL43/Rube-Ster.git
    
    cd Rube-Ster
    
    chmod +x ./install.sh 
    
    ./install.sh 
    
    ruby rube-ster.rb
    
    Langs used :: rust, python, rust, shell script 
    
    summary: rube-ster or Rube-Rabbit is a penetration testing 
    framework built with ruby,rust, python, and shell scripting 
    
    
    NOTE ==> when you want to scan a website go into the scrape.rb file 
    go to where it shows the www.hulu.com as an example replace that 
    with the WWW link of the website, note this is a little buggy the 
    SITE MUST USE IPV4 as this is how it connects and works, working 
    on finding a library. or i might recreate in rust 
    
    ______________________ABOUT___________________________
    well for one let m,e introduce you to Rube-rabbit
    or rubster as i like to call this framework, well  
    Rube-Rabbit is a penetration testing scanner and recon
    framework written mainly from ruby. with ruby being its 
    base it is a very fast fra,ework for port scanning or
    arp scanning the local area network (LAN). i honetsly
    built this framework to see what i could do with ruby 
    there are wya more things to come, and way more options
    coming and even being built in rube-rabbit. in the future
    there will come to be more scripts for scanning, attacking, 
    and maybe even some extra tweaks here and there 
    
    
    
    _________________NEWS/TIPS_____________________________
    Rube-Rabbit or Rubester is a very brand new pentesting 
    and ethical hacking framework meaning it is still 
    in beta and currently under development. no there
    isnt many issues or even issues ive come across so 
    far. however there are some things that make this 
    script a little bit sucky, if you want to scan a website 
    you are going to have to go into the scrape.rb ruby file
    and enter the www. websites. and the website must support
    IPAV4 (internet protocal version 4) as from my own tests
    websites with IPAV6 connections are not supported using 
    the current library, further on i will search for any 
    repos or libs i can use to port scan websites with 
    IPAV6 socks and IPV4 socks. 
    
    
    
    ____________________FEATURES/DO_________________________
    NO rubster is no god legend framework as it was just 
    an experiment that turned out to be something really 
    cool and useful at leats on my end and i hope it is 
    on yours. 

    what can rubster do? well rubster can port scan
    arp scan your local network, install libraries 
    and currently is also up to using basic nmap automation
    rubster uses arpscan to scan the local network, and save 
    it to a pcap file in which tshark is used to load the 
    pcap file and all the mac addresses that were heard from 
    the ARP protocals. 

    when scanning a website rubster uses a list 
    of over 500 average ports for scanning and 
    probing website ports. while also being 
    extremely fast when probing and outputting 
    unlike python3 where i made evil scanner a slow 
    but efficent program this is still one that can 
    be way faster and more useful 
