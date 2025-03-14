---
title: "Uploading Images"
date: 2021-10-06
lastmod: 2024-10-04
weight: 10
draft: false
authors: ["Ed Gilbert","Ben Brandt","Katie Pearson"]
keywords: ["images"]
---

{{< notice info >}}
  This page describes how to upload individual *field* and *specimen* images using the Symbiota portal interface. Technically, images are **not** stored _within_ a Symbiota database. Instead, the URLs of the images are stored. Thus, it is also possible to link images that are stored in external servers. For information about the latter option, visit the [Batch Adding/Linking Images](https://biokic.github.io/symbiota-docs/coll_manager/images/batch/) page.
{{</ notice >}}

Images associated with records in a Symbiota portal may be **Externally Hosted** or **Internally Hosted**.

* **Externally Hosted** images are those stored on servers that are unrelated to the Symbiota portal (e.g., are housed at another institution). These external servers provide image links, which can then be loaded into the Symbiota database.

* **Internally Hosted** images are those stored on servers that are write-accessible to the Symbiota portal server. For example, if you coordinate with Arizona State University to batch upload images to one of their hosted portals (e.g., SEINet, Bryophyte Portal), your images are Internally Hosted.

There are three catefories of images that can be linked to a Symbiota portal. Instructions for uploading individual images of each of these types are provided below. **The below instructions assume that your portal is configured with an image directory that allows upload of images directly through the interface.** This is the case with most portals, but if you run into issues, you may need to contact a portal administrator.

### Individual specimen images

1. Log in to your account in the portal.
2. Navigate to the Occurrence Editor page of the specimen to which you would like to add an image (My Profile > Occurrence Management > name of collection > Edit Existing Occurrence Records > conduct search for specimen)
3. Click the Images tab.

![Images Tab](/symbiota-docs/images/imagestab.png)

4. If an image has already been added to the specimen, and you wish to add another click the green plus sign at the top right of the window. Otherwise, the image uploading interface will be highlighted in yellow on this page.
5. Click the Choose File button and navigate to the image file you wish to upload. If you instead have a URL to the image, you can click Enter URL and paste the URL into the resulting field instead.
6. Enter any additional information, if desired, in the other image uploading fields.

{{< notice tip >}}
   You can enter a number into the Sort field if you wish to define the order in which mutliple images will appear on the occurrence page. If you enter a number greater than 500 in the Sort field, that image will be displayed on the Occurrence Details page but on the Taxon Profile page for that taxon. This is ideal for poor-quality or sensitive images (e.g. road kills). 
{{</ notice >}}

7. Click the Submit New Image button.

### Field image without location information

Images without specific locality information (e.g. lat/long coordinates) are linked only to the scientific name of the organism. These images can be viewed on the Taxon Profile Page, which has general information such as descriptions, distribution maps, synonyms, and common names. To upload an image:

1. Log in to your account in the portal.
{{< notice note >}}
  You must have Taxon Profile Editor permissions to do the following
{{</ notice >}}
2. Navigate to the page of the taxon you wish to edit. To do so, you may be able to:
    *  Click Sitemap, then Taxonomic Tree Viewer or Taxonomy Explorer. Search for the taxon of interest and click its name.
    *  Perform a quick search on the home page for the taxon of interest.
3. Click the pencil icon at the top right corner of the taxon page.
4. Click the Add Image tab.
5. Select the image file you would like to upload from Choose File, then enter any additional information in the provided fields.
    * The **Sort Sequence** field allows you to determine the order of the images that will show up on the taxon profile. The higher the number, the further down the priority list the image will be.
7. Click the Upload Image button.
8. Field images are uploaded and managed through the Taxon Profile Editing interface. Users with Taxon Profile editing permissions can submit an image by clicking on the editing symbol located in the upper right of any Taxon Profile page, or through the image submission links available on the sitemap page. Field images with specific locality details (e.g. coordinates) can be loaded as Image Vouchers (see below). 

### Image Vouchers (field images with location information)

Field images with specific locality information can serve as vouchers for field observations of many birds, mammals, and easy-to-identify plants. There are, however, some taxonomic groups that typically require microscopic or chemical analysis for accurate identification (e.g. lichens, bryophytes, fungi). For such organisms, field images will have limited value. For this reason, some data portals might not allow the submission of observations without a physical specimen.

It is particularly important that images intended as vouchers for an observation be of high quality and clearly display diagnostic morphology of the organism. Data fields required for an image to qualify as a voucher include: observer name, observation date, country, state, locality description, latitude, longitude, and at least one image.

As is the case with images of physical specimen, Image Vouchers are displayed on both the Occurrence Details and the Taxon Profile pages. Image-supported observations can be uploaded in a General Research Observation profile. The following video describes how to gain access to and submit observations to such a collection:

{{< youtube 4uj15JCzHg4 >}} 
