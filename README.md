# information-security-systems-assignment-6-solved
**TO GET THIS SOLUTION VISIT:** [Information-Security-Systems Assignment 6 Solved](https://www.ankitcodinghub.com/product/information-security-systems-assignment-6-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;98700&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Information-Security-Systems Assignment 6 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
• You should have already installed and become familiar with the Ubuntu Mate 20.04 Operating System(OS). You can do this either:

(1) with dual boot i.e. if you already have an OS such as MS Windows, MAC OS, or another linux distribution, just install Ubuntu Mate 20.04 as a secondary OS, or,

(2) by installing first a Virtual machine (e.g. the Oracle VM VirtualBox is freely available) in your existing OS, and then within the VirtualBox installing the Ubuntu Mate 20.04, or, (3) by installing Ubuntu Mate 20.04 as your primary OS.

• If you prefer install the Ubuntu 20.04 OS instead of the Ubuntu Mate.

• You should have already installed the gcc compiler:

sudo apt update

sudo apt install build-essential

• Develop you C code using one of your favorite editors such as gedit, pluma or vi.

Monitoring the network traffic using the Packet Capture library

In this assignment, you will get familiar with the Packet Capture library (libpcap, it is installed by default if you are using Ubuntu Mate 20.04 Operating System) . This assignment assumes background knowledge in network protocols and familiarity with the C programming language.

For more information about the packet capture library, visit the following websites: https://linux.die.net/man/3/pcap, https://www.tcpdump.org.

You are expected to read a pcap file (test_pcap_5mins.pcap ), and you will process the incoming/outcoming TCP and UDP packets. Do not use pcap_compile or pcap_setfilter. For a quick review about TCP protocol have a look at: https://www.tutorialspoint.com/data_communication_computer_network/transmissio n_control_protocol.htm

More specifically, you are expected to do the following:

<ol>
<li>Select the pcap file name.</li>
<li>Start reading packets.</li>
<li>Decode each received TCP or UDP packet</li>
<li>Skip any packet that is not TCP or UDP.</li>
<li>Print the packet’s source and destination IPv4 addresses.</li>
<li>Print the packet’s source and destination port numbers.</li>
<li>Print the packet’s protocol (please include higher level protocols e.g http)</li>
<li>Print the packet’s TCP/UDP header length and TCP/UDP payload length in bytes.</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<ol start="9">
<li>Can you tell if an incoming TCP packet is a retransmission? If yes, how? If not, why?</li>
<li>Can you tell if an incoming UDP packet is a retransmission? If yes, how? If not, why?</li>
<li>In your program (when possible), mark each retransmitted packet as “Retransmitted”.</li>
<li>On exit, your program must print the following statistics:

a. Total number of network flows captured. Be careful what is and what is not a network flow using this definition: A network flow is a 5-tuple consisted of : {source IPv4 address, source port, destination IPv4 address, destination port, protocol}.

b. Number of TCP network flows captured.

c. Number of UDP network flows captured.

d. Total number of packets received (include the packets you skipped, that weren’t TCP or UDP packets.).

e. Total number of TCP packets received.

f. Total number of UDP packets received.

g. Total bytes of TCP packets received.

h. Total bytes of UDP packets received.</li>
</ol>
Tool Specification

Your tool will receive the following arguments from the command line upon execution. Options:

-r Packet capture file name (e.g. test.pcap) -h Help message

Notes

<ol>
<li>The options defined in the “Tool specification” section must remain as-is.</li>
<li>If no appropriate option was given, your program has to print the appropriate error
message.
</li>
<li>You need to create a Makefile to compile your library and programs (you must
submit it with your source code).
</li>
<li>You are provided with a sample packet capture to test your program. Its duration is 5
minutes.
</li>
<li>You need to submit all the source code of your tool: a “Makefile”, “monitor.c”, and a
“README.txt” file that explains briefly your implementation and what you didn’t implement and why. Place all these files in a folder named &lt;yourlastnameAM&gt;_assign6, and then compress it as a .zip file that you will upload to eclass. For example: christodoulou2018123456_assign6.zip.
</li>
<li>The README.txt file is important to submit.</li>
<li>Very important: execute the command gcc –-version and write whatever the output
is into your README.txt file, e.g. “gcc (Ubuntu 9.3.0-10ubuntu2~20.04)”
</li>
</ol>
</div>
</div>
</div>
