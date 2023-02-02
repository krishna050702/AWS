<h2> AWS Stoarge Classes </h2>

![AWS S3 in Detail](/assets/aws-storage-classes.jpg)

<h3 style="color:blue;font-family:rog;"> S3 contains four types of Stoarge Classes </h3>
<ul>
<li> S3 Standard
<li> S3 Standard IA
<li> S3 one zone-infrequent access
<li> S3 Glacier
</ul>

<h4 style="color:brown;"> S3 Standard </h4>
<ul>
<li> It stores the data redundantly across multiple devices in multiple facilities.
<li> It is designed to sustain 2 facilities concurrently.
<li> Is default storage class if none of the storage class is specified during upload.
<li> It provies low latency and high throughput performance.
<li> It is designed for 99.99% availability and 99.999999% durability.
</ul>

<hr>
<h4 style="color:brown;"> S3 Standard IA</h4>
<ul>
<li> IA stands for <i>Infrequently Accessed.</i>
<li> Standard IA storage class is used when data is accessed less frequently but requires rapid access when needed.
<li> It has a lower fee than S3, but you will be charged for a retrieval fee.
<li> It is mainly used for larger objects greater than 128 KB kept for atleast 30 days.
</ul>

<hr>
<h4 style="color:brown;"> S3 one zone-infrequent access</h4>
<ul>
<li> S3 one zone-infrequent access storage class is used when data is accessed less frequently but requires rapid access when needed.
<li> It stores the data in a single availability zone while other storage classes store the data in a minimum of three availability zones. Due to this reason, its cost is 20% less than Standard IA storage class.
<li> It is cost-effective storage which is replicated from other AWS region using S3 Cross Region replication.
<li> It has the same durability, high performance, and low latency, with a low storage price and low retrieval fee.
</ul>

<hr>
<h4 style="color:brown;"> S3 Glacier</h4>
<ul>
<li> S3 Glacier storage class is the cheapest storage class, but it can be used for archive only.
<li> S3 Glacier provides three types of models:
<ul>
<li> <b>Expedited:</b> In this model, data is stored for a few minutes, and it has a very higher fee.
    <li> <b>Standard:</b> The retrieval time of the standard model is 3 to 5 hours.
    <li> <b>Bulk:</b> The retrieval time of the bulk model is 5 to 12 hours.
</ul>
</ul>

<h4>Summary:- </h4>

![Performance across the Stoarge Classes](/assets/S3_comparison.png)

<hr>

<h4 style="color:brown;"> Versioning </h4>
<ul>
<li> It means of keeping the multiple forms of an object in the same S3 bucket. Versioning can be used to retrieve, preserve and restore every version of an object in S3 bucket.
<ul>
<li> If you delete an object, instead of deleting the object permanently, it creates a delete marker which becomes a current version of an object.
<li> If you overwrite an object, it creates a new version of the object and also restores the previous version of the object.
</ul>
</ul>

