# cs252-lab-05-csma-ca-study-using-ns3-solved
**TO GET THIS SOLUTION VISIT:** [CS252 Lab 05-CSMA/CA study using ns3 Solved](https://www.ankitcodinghub.com/product/cs252-lab-05-ieee-802-11-csma-ca-study-using-ns3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;113576&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS252  Lab 05-CSMA\/CA study using ns3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
This lab should be done individually.

1. Download the ns3 code file lab05-wifi-2hidden-stns.cc. This file models 3 stations n0, n1 and n2, in a configuration such that n1-n0 can hear each other, n2-n0 can hear each other, but n1 – n2 cannot. Thus n1, n2 are hidden terminals w.r.t. each other.

Study the code – it is well-commented, make sure you understand every line. The basic concept of an abstract helper object which gets installed on some concrete object representing an actual networking entity is the same as you studied in the previous lab. Move the file to scratch directory and run it as you learnt in the previous lab.

First look at the code carefully and find out the following (don’t give answers to these in your report):

What is the mechanism used in the code to achieve the topology of ‘hidden-ness’ vs reachability of the nodes?

Which particular one of the 802.11 family of protocols is selected in this simulation (for PHY layer)

What is the data rate of the channel?

What is the flow configuration? (Who’s sending what to whom?) What are the flow parameters?

Run the simulation using ./waf –run lab05-wifi-2hidden-stns and in your report give the answers for the following questions. Wherever applicable answer all questions for with and without RTS/CTS.

a. For the default parameters, what’s the per node throughput? What’s the total channel throughput?

b. Change the values so that the total data rate offered to the channel (that is sum of data rates of all CBR flows) is about 10% of the channel data rate, equally divided among all sources (keep “dataRate” for all sources the same). Keep increasing offered load to 20%, 30% … 90%. What’s the total throughput achieved for each value? What is the trend of the throughput vs offered load? Plot the values.

Note: You should not touch the “payload” value. Instead change offered load using the “dataRate” parameter.

c. Find out the total throughput possible when there is no contention (only one source).

d. Make any observations of the numbers with and without RTS/CTS

2. RTS/CTS was designed mainly to solve the hidden terminal problem. So perhaps it is not very useful when there aren’t hidden terminals? Modify the code and design and run experiments to validate/invalidate this hypothesis. You need to ensure that all nodes can hear each other. Give answers to the following questions:

a. Change the values so that the total data rate offered to the channel (that is sum of data rates of all CBR flows) is about 10% of the channel data rate, equally divided among all sources. Keep increasing it to 20%, 30% … 90%. What’s the total throughput achieved for each value? What is the trend of the throughput vs offered load? Plot the values.

b. Make any observations of the numbers with and without RTS/CTS

3. We revisit two Wi-Fi scenarios you have encountered in CS224 in Figures 1 and 2. All WiFi nodes use virtual carrier sensing (RTS/CTS) to solve the hidden terminal problem. Assume that any node can both carrier sense and also receive packets (RTS, CTS, DATA, or ACK) from another node if and only if the two nodes are within distance 3 units of each other. Assume that no DATA packets are sent between pairs of nodes other than the ones explicitly mentioned below.

In Figure 1 we see six Wi-Fi nodes located on a two-dimensional plane: A1 , B1, and C1 at (1,0), (3,0), and (5,0) respectively, and A2 , B2 , and C2 at (1,2), (3,2), and (5,2) respectively. Assume that A1 has a CBR flow to send to A2, B1 has a CBR flow to send to B2, C1 has a CBR flow to send to C2.

Figure 1

Modify the code of lab05-wifi-2hidden-stns.cc to simulate the above scenario. You don’t have to physically place nodes at the locations shown, but ensure that each node can only hear other nodes based on the problem statement above.

a. For the default parameters of CBR rate (same as in lab05-wifi-2hidden-stns.cc) what’s the per node throughput? What’s the total channel throughput? You can use the same simulation stop time as lab05-wifi2hidden-stns.cc.

b. Change the values of CBR data rate so that the total data rate offered to the channel is about 10% of the channel data rate, equally divided among all sources. Keep increasing it to 20%, 30% … 90%. What’s the total throughput achieved for each value? What is the trend of the throughput vs offered load? Plot the values.

c. Comment on your observations, and suggest reasons for the observations.

4. All WiFi nodes use virtual carrier sensing (RTS/CTS) to solve the hidden terminal problem. Assume that any node can both carrier sense and also receive packets (RTS, CTS, DATA, or ACK) from another node if and only if the two nodes are within distance 3 units of each other. Assume that no DATA packets are sent between pairs of nodes other than the ones explicitly mentioned below.

In Figure 2 we see four Wi-Fi nodes located on a two-dimensional plane: A, B, C and D located at (0,0), (2,0), (4,0), and (6,0) respectively.

Figure 2

Modify the code of lab05-wifi-2hidden-stns.cc to simulate the above scenario. You don’t have to physically place nodes at the locations shown, but ensure that each node can only hear the nodes based on the problem statement above.

a. For the default parameters of CBR rate (same as in lab05-wifi-2hidden-stns.cc) what’s the per node throughput? What’s the total channel throughput? You can use the same simulation stop time as lab05-wifi2hidden-stns.cc.

b. Change the values of CBR data rate so that the total data rate offered to the channel is about 10% of the channel data rate, equally divided among all sources. Keep increasing it to 20%, 30% … 90%. What’s the total throughput achieved for each value? What is the trend of the throughput vs offered load? Plot the values.

c. Comment on your observations, and suggest reasons for the observations. Submission Instructions:

1. Make a folder named &lt;roll_number&gt;_lab05

2. Place files q2.cc , q3.cc, q4.cc, report.pdf in that folder

3. Submit a tar zipped file &lt;roll_number&gt;_lab05.tar.gz. Use following command:

tar -czvf &lt;roll_number&gt;_lab05.tar.gz &lt;roll_number&gt;_lab05
