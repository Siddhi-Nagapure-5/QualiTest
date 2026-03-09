Important Research

1️⃣ Medicine Label / Packaging Data (For OCR Testing)

You need images where the system can read:

Medicine name

Batch number

Expiry date

Manufacturer

Sources

Take photos of medicine strips/boxes at home 📸

Ask friends for different medicines

Use Google Images for sample packaging

Search examples:

paracetamol medicine strip
medicine packaging batch number
pharmaceutical label packaging

This helps train/test your OCR extraction.

2️⃣ Medicine Database (Reference Information)

Your system should know things like:

valid medicine names

manufacturer

batch formats

Good open datasets
WHO Medicines Database

Organization: World Health Organization

Website:
https://www.who.int/medicines

Contains:

essential medicines list

drug information


DrugBank

DrugBank

Website:
https://go.drugbank.com/

Contains:

medicine details

drug composition

manufacturers

FDA Drug Database

U.S. Food and Drug Administration

Website:
https://www.fda.gov/drugs

Contains:

approved drugs

manufacturing information

3️⃣ Image Datasets (Optional for ML)

If you want real ML training, you need datasets.

Kaggle

Kaggle

Search datasets like:

medicine packaging dataset
pharmaceutical blister pack dataset
medical pill dataset
pill image recognition dataset

Examples:

Pill Image Recognition Dataset

Pharmaceutical Blister Pack Dataset

4️⃣ Defect Detection Data

If your system detects damaged packaging, you can use generic defect datasets.

Example datasets:

industrial defect detection

packaging damage dataset

These help train CNN models.

5️⃣ Expiry Detection Research

You don't need a dataset here — just OCR extraction.

Example text:

EXP: 05/2027
Batch: BX245

Your logic simply checks:

expiry_date < current_date

6️⃣ Statistical Research

To make your dashboards meaningful, research:

pharmaceutical quality control

batch failure rates

supply chain traceability

Good sources:

PubMed

Google Scholar

WHO reports

Search terms:

pharmaceutical quality monitoring
drug batch tracking system
medicine supply chain traceability

7️⃣ Minimum Data You Actually Need (For MVP)

You can start with just:

20–30 medicine package images
OCR extraction
Expiry check logic
Simple quality scoring

That's enough for first prototype.


8️⃣ Example Dataset You Can Create Yourself

Create folder:

dataset/
   medicine_images/

Add images like:

paracetamol1.jpg
vitamin_c_strip.jpg
antibiotic_box.jpg

Then test:

OCR extraction
quality logic


https://www.figma.com/make/HVXSGgpd7Ncq45GZhAYmnh/QualiTest-Web-App-UI-Design?fullscreen=1&t=mF8nJdBqgQqw4FfK-1