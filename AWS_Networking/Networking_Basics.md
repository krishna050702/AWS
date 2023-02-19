<h3>Networking Basics</h3>
<ul>
<li><p>A computer network is two or more client machines that are connected together to share resources.</p></li>
<li><p>A network can be logically partitioned into subnets.</p></li>
<li><p>Networking requires a networking device (such as a router or switch) to connect all the clients together and
enable communication between them.</p></li>
<li><p><img src="../assets/networks_subnet.png"/></p></li>
</ul>
<hr>
<ul>
<li><p>Each client machine in a network has a unique Internet Protocol (IP) address that identifies
it.</p></li>
<li><p>An IP address is a numerical label in decimal format. Machines convert that decimal number to a binary format.</p></li>
<li><p>A 32-bit IP address is called an IPv4 address. and IPv6 has 128 bits.</p></li>
<li><p><img src="../assets/ip_address.png"/> </p></li>
</ul>
<hr>
<ul>
<li><p>A common method to describe networks is Classless Inter-Domain Routing (CIDR). The CIDR address is expressed as follows:- </p>
<ul>
<li><p>An IP address(which is the first address of the network.</p></li>
<li><p>Next, a slash character (/).</p></li>
<li><p>At last, a number that tells you how many bits of the routing prefix must be fixed or allocated for the network identifier.</p></li>
</ul>
</li>
<li><p>The bits that are not fixed are allowed to change. CIDR is a way to express a group of IP addresses that are consecutive to each other.</p></li>
<li><p>In this example, the CIDR address is 192.0.2.0/24. The last number (24) tells you that the
first 24 bits must be fixed. The last 8 bits are flexible, which means that 2<sup>8</sup> (or 256) IP addresses are available for the network, which range from 192.0.2.0 to 192.0.2.255. The
fourth decimal digit is allowed to change from 0 to 255.</p></li>
<li><img src="../assets/cider.png"/> </li>
</ul>

<hr>
<ul>
<li><img src="../assets/osi_model.png"/> </li>
<li><p>Also have a look on the OSI model, it can also be used to understand how communication takes place in a virtual private cloud(VPC).</p></li>
</ul>

<hr>