# gcp-cud-guide
Tips on how to use commited use discounts(CUD) on  Google Cloud Plataform 

The term [commited use discounts](https://cloud.google.com/compute/docs/instances/signing-up-committed-use-discounts) refers to a contract you do with GCP on which you agree to pay a specific amount of money
for a specific number of resources for a period of 1 or 3 years and in return GCP gives you up to 70% of discount on those resources.

Q: Which type of resources can get CUDs?<br>
A: [vCPUs, memory, GPUs, local SSDs, and sole-tenant nodes](https://cloud.google.com/compute/docs/instances/signing-up-committed-use-discounts#:~:text=vCPUs%2C%20memory%2C%20GPUs%2C%20local%20SSDs%2C%20and%20sole%2Dtenant%20nodes)


Q: CUDs can be shared and/or dedicated?<br>
A: [Yes. You can use CUD on a sigle project or on mutiple projects.](https://cloud.google.com/compute/docs/instances/signing-up-committed-use-discounts#:~:text=You%20can%20purchase%20a%20committed%20use%20contract%20for%20a%20single%20project%2C%20or%20purchase%20multiple%20contracts%20which%20you%20can%20share%20across%20many%20projects%20by%20enabling%20shared%20discounts.)

Q: What is the default behavior for CUD sharing?<br>
A: [By default CUDs are not shared. If you want to share, you have to enable it.](https://cloud.google.com/compute/docs/instances/signing-up-committed-use-discounts#:~:text=By%20default%2C%20committed%20use%20discounts%20are%20applied%20to%20the%20project%20where%20you%20purchased%20it.)

Q: What happens if I don't use the resources I comiited with?<br>
A: [Google charges you for the resources you commited with. Doesn't matter if you use it or not.](https://cloud.google.com/compute/docs/instances/signing-up-committed-use-discounts#:~:text=After%20purchasing%2C%20you%20are%20billed%20monthly%20for%20the%20resources%20you%20purchased%20for%20the%20duration%20of%20the%20term%20you%20selected%2C%20whether%20or%20not%20you%20use%20the%20services.)

Q: What happens if I don't use the resources I comiited with?<br>
A: [Google charges you for the resources you commited with. Doesn't matter if you use it or not.](https://cloud.google.com/compute/docs/instances/signing-up-committed-use-discounts#:~:text=After%20purchasing%2C%20you%20are%20billed%20monthly%20for%20the%20resources%20you%20purchased%20for%20the%20duration%20of%20the%20term%20you%20selected%2C%20whether%20or%20not%20you%20use%20the%20services.)

Q: Does CUD require any upfront payment?
A: [No.](https://cloud.google.com/compute/docs/instances/signing-up-committed-use-discounts#:~:text=require%20no%20upfront%20costs)

Q: Do I have to match a CUD offer with a instance/vm offer?
A: No. CUD apply to the aggregate number of vCPUs, memory, GPUs, and local SSDs within a region

Q: Are there exceptions on which CUD do not apply?
A: [Yes. 50, 75, and 100 Gbps higher bandwidth SKUs,F1-micro and g1-small shared-core machines are not eligible for committed use discounts.](https://cloud.google.com/compute/docs/instances/signing-up-committed-use-discounts#:~:text=Although%20N2%20and,committed%20use%20discounts)

Q: Can I commit to pay for 10 vcpu per month and use 20 vcpu during 15 days?
A: [No. CUD are applied to exact number of CPU you commited to, no matter how much time you run than.](https://cloud.google.com/compute/docs/instances/signing-up-committed-use-discounts#:~:text=Commitments%20can%27t%20be%20stacked%20for%20burst%20scenarios.%20For%20example%2C%20if%20you%20purchased%2010%20cores%20for%20the%20month%20and%20then%20ran%2020%20cores%20for%20half%20the%20month%2C%20commitments%20would%20not%20apply%20for%20the%20full%2020%20cores%20just%20because%20the%20usage%20was%20half%20the%20month.)

Q: Can I combine CUD and SUD (sustained use discounts)?
A: [No.]()
