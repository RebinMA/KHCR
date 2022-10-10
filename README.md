## Kurdish Handwritten Character Recognition Using CNN in TensorFlow

Handwriting recognition is one of the active and challenging areas of research in the field of image processing and pattern recognition. It has many applications that include: a reading aid for the blind, automated reading and processing for bank checks, making any handwritten document searchable, and converting them into structural text form. Moreover, high accuracy rates have been recorded by handwriting recognition systems for English, Chinese, Arabic, Persian, and many other languages. Yet there is no such system available for offline Kurdish handwriting recognition.

In this paper, an attempt is made to design and develop a model that can recognize handwritten characters for the Kurdish alphabet using deep learning techniques. Kurdish (Sorani) contains 34 characters and mainly employs an Arabic\\Persian based script with a modified alphabet. In this work, a Deep Convolutional Neural Network model is employed that has shown exemplary performance in handwriting recognition systems. Then, a comprehensive dataset was created for handwritten Kurdish characters, which contains more than 40 thousand images. The created dataset has been used for training the Deep Convolutional Neural Network model for classification and recognition tasks.

In the proposed system, the experimental results show an acceptable recognition level. The testing results reported a 96% accuracy rate, and training accuracy reported a 97% accuracy rate. From the experimental results, it is clear that the proposed deep learning model is performing well and is comparable to the similar model of other languages' handwriting recognition systems.

## Dataset
Finding a suitable source of data is considered a first step toward building a database. The first step in building a database is finding a suitable source. Here, the main goal is to collect images of Kurdish handwritten characters written by many writers. So, a form is designed to do so. The form is shown in Figure 1. It consists of 1 alphabet at a time letter that has been printed on the top right corner, and it has 125 empty blocks. The writers have been asked to write each letter three times in the three empty blocks. The total number of writers is 390.
The forms have been distributed among two main categories: The academic staff of the Information Technology department at Tishk International University, the university students of the University of Kurdistan-Hawler, Salahaddin University, and Tishk International University As shown in Table 2. 
In total there were ten sets of forms, each set with 35 forms for 35 different letters, at first, we decided that nine sets, which will give us at least 1100 images for each letter were the best option for the time that we had. Then there were some problems with the collection process, in first prints of the forms there was confusion for instance in Set 2, there were 2 forms for the letter (چ) and none for (ج), and since we printed and distributed the form at the same time, we were not aware of this problem until the stage of pre-processing, This was creating an inconsistency in the number of samples that we had, for example by the 9th set we had 504 images of the letter (ڤ), which was much less than other letters that they had at least 1000 images. So we decided to add the 10th set as a complementary to other sets, it only contained those letter, which was missing in the first 9 forms, which was (ز،ژ،ش،غ،ڤ،ق،ک،ل،ن،ی), as explained in Table 3, the First column is the letter and columns 2-11 represent several images gathered in each set accordingly, while the first row the header row 2-36 are letters in each set, last row, and last columns are for the total of each letter and each set.

[An Extensive Dataset of Handwritten Central Kurdish Isolated characters](https://github.com/RebinMA/An-Extensive-Dataset-of-Handwritten-Central-Kurdish-Isolated-characters)


## Citations

Cite the following articles:

Rebin M.Ahmed, Tarik A. Rashid, Polla Fattah, Mohammed Kamal Majeed, Abeer Alsadoon, Nebojsa Bacanin, Seyedali Mirjalili, S.Vimal, Amit Chhabra. 2022. Kurdish Handwritten character recognition using deep learning Gene Expression Patterns.[DOI: https://doi.org/10.1016/j.gep.2022.119278](https://doi.org/10.1016/j.gep.2022.119278)

Rebin M. Ahmed, Tarik A. Rashid, Polla Fatah, Abeer Alsadoon, Seyedali Mirjalili (2021). An Extensive Dataset of Handwritten Central Kurdish Isolated characters, Data in Brief, 107479. [DOI:](https://doi.org/10.1016/j.dib.2021.107479) [https://doi.org/10.1016/j.dib.2021.107479](https://doi.org/10.1016/j.dib.2021.107479)

M. Ahmed, Rebin; Rashid, Tarik; Fattah, Polla (2020), “An extensive dataset of Handwritten Central Kurdish Isolated characters.”, Mendeley Data, [DOI:](http://dx.doi.org/10.17632/f8z9jts5nb) [https://dx.doi.org/10.17632/f8z9jts5nb](http://dx.doi.org/10.17632/f8z9jts5nb)

## Contributing

If you'd like to contribute or have any suggestions for these guidelines, you can contact us at rebin.mahmed@gmail.com or open an issue on this GitHub repository.

All contributions are welcome! All content in this repository is licensed under the MIT license.