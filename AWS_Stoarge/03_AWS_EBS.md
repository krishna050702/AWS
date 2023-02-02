<h3 style="color:brown;">AWS EBS</h3>

<ul>
<li> It is also called as Elastic Block Store.
<li> EBS volumes are used for data that needs to persist.
<li> It is important to backup the data with AWS EBS snapshots.
<li> After creating an EBS volume, you can attach it to an AWS EC2 instance.
<li> If the EC2 instance stops or is terminated, all the data on the attached EBS volume remains.
</ul>

<h4 style="color:brown;">What are AWS EBS Snapshots?</h4>
<ul>
<li> It is an incremental data backup.
<ul>
<li> The first backup of a olume backups all the data.
<li> Every next backup copies only a block of data that has changed since the last snapshot.
<li> It saves on storage costs by not duplicating data.
</ul>
<li> Only tha data unique to that snapshot is removed when you delete a snapshot
<li> ![EBS Snapshots](/assets/ebs_snapshots.jpg)

</ul>