## Publication

### Few general practices.
1. If the study//publication is external, we dont add the pdf file, we just link the thumbnail to the external website.
2. If the study//publication is internal. we add the pdf in the backend, and we link the thumbnail to that file location.
3. Always Optimize the PDFs for web viewing before uploading using online tools like(https://www.pdf2go.com/linearize-pdf).
4. Always convert thumbnail and other images to .jpg format to keep the file size low.
5. Always compress the thumbnail image and all study images using tools like(https://www.iloveimg.com/compress-image) (Generally images should be less than 70kb after compression.)
5. If the footnotes of images consists of multiple lines, use <br> to push the text to next line instead of a <p> as it creates no line spacing in the text.
6. Hyperlink all the SEO keywords shared by the SEO team, add target="_blank" to add the hyperlinked words so that it opens a new tab.


### An unusual error
-There might be a case the the first page of the pdf is shown as blank white even if the page is visible when opened locally on the system.
How to solve it?
- Split the .pdf in 2 parts, the first page and te test of the file. Use the tool(https://www.ilovepdf.com/split_pdf)
- Take the screenshot of the 1st page by opening it locally and save the image as .png.
- Convert the .png image to .pdf. Use the tool(https://png2pdf.com/)
- Join this created .pdf of 1st page with the rest of the file extracted in the step 1.(https://pdfjoiner.com/)
- Repeat the step to optimize the pdf for web


#### There are 2 types of Publication template:
1. Old template(Publication)
2. New template(Publication Dynamic)


#### Adding Publication Content on Old Template.
#### Old Template- 
1. Review the content, number of bullet points, subheadings, images used etc. and find a similar publication using the same format. 
2. Click on find content and search by name for the publication that has been already published, click on source and copy. (Keep this open on this current tab)
3. Open a new tab and click on add content, publications and change textbox dropdown to full HTML. Click on source and paste the content. Add the title of the new publication too. 
4. You can toggle between source code view and text edit box view by clicking on Source. 
5. Make the necessary text changes in citation, overview, key findings/highlights, recommendations etc. At the bottom of the page, there will also be one liner highlight. 
6. Add subtitle if any, change date, publication type, add cover image (below date) by taking a screenshot of the PDF cover.
7. For authors, there are two cases:
- If all CEEW authors, then search for their names in the author box, add comma and edd each name
- If a mix of CEEW and outside authors, add CEEW authors in the authors search box and add all authors (including CEEW ones) in the ‘All Authors’ text box in the order to be presented. 
8. Upload PDF to the PDF full book option, then go back to the body box, click on source and change path of the old PDF to the new PDF
9. Ignore Download PDF, PUblisher’s PDF, Citation, Chapter wise and other Publication buttons.
10. Search for the Tags and pick the query author. Ignore New tag and Twitter Code. 
11. Change URL Paths based on SEO and add meta title. 
12. Click on publishing options and unpublished to check if everything is working. If all is fine, publish.


#### New Template- 
1. Repeat the process of finding a publication with the similar format, opening in a new tab. This can be found by filtering using Publication Dynamic in find content. Don’t copy anything yet
2. On a new tab, click on add content and pick publication dynamic. Select type of publication as template 2, add title in both fields, subtitle and same logic for authors as mentioned above. 
3. Add citation in the citation box after changing to Full HTML
4. Add focus area/tag focus area. Upload PDF or PDF link after uploading on Filezilla. 
5. Add Download Study button with link in dataset links, add one more button if needed. Add PDF thumbnail (the cover image) like before. 
6. For the key findings box, change to full HTML and copy CSS from an already published publication (style tag). Then add overview, key findings, embedding video/images as required. This represents the grey box. 
7. Add query author and quote, check an already published publication for the same. 
8. Add content in the executive summary box with summary title representing each section that appears in the indexing box on the right of the page. 
9. Click add another item to increase the number of sections. 
10. Executive summary head is for the information before the section breaks. Normally a para or two is added here. 
11. In some cases, there will be no section breaks where the entire content will be added in the executive summary head box. 
12. Ensure all are Full HTML
