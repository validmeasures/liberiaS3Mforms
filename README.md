# liberiaS3Mforms: Liberia Coverage Survey XLSform and Xform Instruments <img src="figures/s3m_neg.png" align="right" />

[![DOI](https://zenodo.org/badge/143430021.svg)](https://zenodo.org/badge/latestdoi/143430021)

The Liberia Coverage Survey for the assessment of CMAM coverage, micronutrient powder supplementation coverage, vitamin A supplementation coverage, iron folic acid supplementation coverage and IYCF counselling coverage has been commissioned by [UNICEF Liberia]() with funding from [Power of Nutrition](http://www.powerofnutrition.org/).

In support of this survey, the following survey instruments in XLSform and Xform standard for [Open Data Kit](https://opendatakit.org/) have been developed.

## Village form

This form (`liberiaCoverageVillageForm.xlsx` and `liberiaCoverageVillageForm.xml`) collects information on the villages or primary sampling units (PSU) selected for the Liberia Coverage Survey. This information includes:

1. County name (and identifier)

2. Village name (and identifier)

3. Village population size 

4. Village geocoordinates

## Coverage form

This form (`liberiaCoverage.xlsx` and `liberiaCoverage.xml`) collects information on the various coverage indicators assessed in the Liberia Coverage Survey:

1. CMAM coverage

2. Iron-folic acid supplementation coverage

3. IYCF counselling coverage

4. Micronutrient powder supplementation coverage

5. Vitamin A supplementation coverage

The coverage form has been developed in such a way that it implements the survey as per survey design such that the modules for IFA coverage, IYCF counselling coverage, MNP supplementation coverage and vitamin A supplementation coverage are only shown based on the sampling interval for a particular primary sampling unit (PSU) and based on the different eligibitlity requirements for each coverage survey module.

## Usage

For those wanting to test out the forms on their own Android mobile devices, the following applications need to be downloaded and installed from the Google Play Store:

* ODK Collect ([link](https://play.google.com/store/apps/details?id=org.odk.collect.android&hl=en_GB))

* ODK Counter ([link](https://play.google.com/store/apps/details?id=org.opendatakit.counter&hl=en_GB))

Once these applications are isntalled, there are two option for getting the Liberia Coverage Survey forms onto mobile devices.

### 1. Using ODK Aggregator or other similar ODK servers
The XLSForm can be uploaded to a remote server-based ODK Aggregator or other ODK servers such as ONA, SurveyCTO, KoBoToolbox and the like. The form is validated and then converted into XML format which can then be retrieved from the server into mobile devices as blank forms.

For the purposes of viewing and testing the Liberia Coverage Survey forms, a test server has been setup. To view and/or test the Liberia Coverage Survey forms, ODK Collect in the mobile devices will need to be connected to the server. This is described [here](https://docs.opendatakit.org/collect-connect-aggregate/). The following ODK Aggregate server setttings should be used:

&nbsp;

**url**: https://odk.ona.io

**username:** validtrial

**password:** zEF-STN-5ze-qom

&nbsp;

Once ODK Collect has been connected to the test server, it will now be possible to pull the Liberia Coverage Survey forms into ODK Collect in the mobile device using the instructions found [here](https://docs.opendatakit.org/collect-forms/).

Once the Liberia Coverage Survey forms have been pulled into the ODK Collect in the mobile device, the forms can be viewed and tested by following the instructions [here](https://docs.opendatakit.org/collect-filling-forms/).

### 2. Convert to XML and transfer to mobile devices via USB cable connection
This XLSForm can be converted to XML format using XLSForm Offline from Nafundi. The XML format can then be transferred to the mobile devices (into the device's odk folder) via local USB connection. This can be done by following the instructions [here](https://docs.opendatakit.org/collect-forms/#loading-forms-directly). The associated media files for the forms (found in the folder called `media`) will also need to be transferred to the mobile device. This can be done by following the instructions [here](https://docs.opendatakit.org/collect-forms/#loading-form-media). 

## Author
Ernest Guevarra

## License
MIT License
