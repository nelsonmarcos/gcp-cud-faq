# gcp-cud-faq
A FAQ about commited use discounts(CUD) on  Google Cloud Plataform 

The term [commited use discounts](https://cloud.google.com/compute/docs/instances/signing-up-committed-use-discounts) refers to a contract you do with GCP on which you agree to pay a specific amount of money, for a specific number of resources, for a period of 1 or 3 years. In return, GCP gives you a discount based on machine type and period of commitment.

Q: How much discount can I get?
A: [On specific commits you get get up to a 70% discount. BUT it will vary according to the region, machine type and period of commitment.](https://cloud.google.com/compute/docs/instances/signing-up-committed-use-discounts#:~:text=The%20discount%20is%20up%20to%2057%25%20for%20most%20resources%20like%20machine%20types%20or%20GPUs.%20The%20discount%20is%20up%20to%2070%25%20for%20memory%2Doptimized%20machine%20types.)

Q: Which type of resources can get CUDs?<br>
A: [vCPUs, memory, GPUs, local SSDs, and sole-tenant nodes](https://cloud.google.com/compute/docs/instances/signing-up-committed-use-discounts#:~:text=vCPUs%2C%20memory%2C%20GPUs%2C%20local%20SSDs%2C%20and%20sole%2Dtenant%20nodes)

Q: Can I buy CUD to be shared among projects? Can I buy CUD and apply then to a specific project?<br>
A: [Yes for both. You can use CUD on a sigle project or on mutiple projects.](https://cloud.google.com/compute/docs/instances/signing-up-committed-use-discounts#:~:text=You%20can%20purchase%20a%20committed%20use%20contract%20for%20a%20single%20project%2C%20or%20purchase%20multiple%20contracts%20which%20you%20can%20share%20across%20many%20projects%20by%20enabling%20shared%20discounts.)

Q: What is the default behavior for CUD sharing?<br>
A: [By default CUDs are not shared. If you want to share, you have to enable it.](https://cloud.google.com/compute/docs/instances/signing-up-committed-use-discounts#:~:text=By%20default%2C%20committed%20use%20discounts%20are%20applied%20to%20the%20project%20where%20you%20purchased%20it.)

Q: What happens if I don't use the resources I commited with?<br>
A: [Google charges you for the resources you commited with. Doesn't matter if you use it or not.](https://cloud.google.com/compute/docs/instances/signing-up-committed-use-discounts#:~:text=After%20purchasing%2C%20you%20are%20billed%20monthly%20for%20the%20resources%20you%20purchased%20for%20the%20duration%20of%20the%20term%20you%20selected%2C%20whether%20or%20not%20you%20use%20the%20services.)

Q: Does CUD require any upfront payment?<br>
A: [No.](https://cloud.google.com/compute/docs/instances/signing-up-committed-use-discounts#:~:text=require%20no%20upfront%20costs)

Q: Do I have to match a CUD offer with a instance/vm offer?<br>
A: [Yes, you have to match the instance type](https://cloud.google.com/compute/docs/instances/signing-up-committed-use-discounts#:~:text=Purchase%20the%20appropriate%20commitment%20type%20for%20the%20machine%20types%20you%20are%20using.) [but you don't have to match number of vCPU, memory and etc since CUD apply to the aggregate number of resources within a region](https://cloud.google.com/compute/docs/instances/signing-up-committed-use-discounts#:~:text=For%20example%2C%20assume%20you%20have%20a%20region%20with%20the%20following%20mix%3A)

Q: Are there exceptions on which CUD do not apply?<br>
A: [Yes. 50, 75, and 100 Gbps higher bandwidth SKUs,F1-micro and g1-small shared-core machines are not eligible for committed use discounts.](https://cloud.google.com/compute/docs/instances/signing-up-committed-use-discounts#:~:text=Although%20N2%20and,committed%20use%20discounts)

Q: What if I commit to pay for 10 vcpu per 30 days but actually use 20 vcpu during 15 days? Will my cud be shared among the 20 vcpus?<br>
A: [No. CUD are applied to exact number of CPU you commited to, no matter how much time you run than.](https://cloud.google.com/compute/docs/instances/signing-up-committed-use-discounts#:~:text=Commitments%20can%27t%20be%20stacked%20for%20burst%20scenarios.%20For%20example%2C%20if%20you%20purchased%2010%20cores%20for%20the%20month%20and%20then%20ran%2020%20cores%20for%20half%20the%20month%2C%20commitments%20would%20not%20apply%20for%20the%20full%2020%20cores%20just%20because%20the%20usage%20was%20half%20the%20month.)

Q: Can I combine CUD and SUD (sustained use discounts)?<br>
A: [No.](https://cloud.google.com/compute/docs/instances/signing-up-committed-use-discounts#:~:text=Any%20resources%20that%20do%20not%20qualify%20for%20committed%20use%20discounts%20automatically%20qualify%20for%20sustained%20use%20discounts.%20You%20can%27t%20combine%20committed%20use%20discounts%20and%20sustained%20use%20discounts%20for%20the%20same%20resources.)

Q: Can I shared CUD among mutilple regions?<br>
A:[No. CUD are region specific so you must make a commitment for each region for which you want to use CUD.](https://cloud.google.com/compute/docs/instances/signing-up-committed-use-discounts#:~:text=Commitments%20must%20be%20purchased%20on%20a%20per%2Dregion%20basis.)
