# My CV Template

<!--
command to convert a pdf page to png
convert -density 200 main.pdf\[\0] -quality 100 -resize 50% -background white -flatten coverletter.png
-->

<div>
  <img src="https://github.com/nidzov/nidzocv/blob/master/media/coverletter.png" alt-="cv example" width="300px"/>
  <img src="https://github.com/nidzov/nidzocv/blob/master/media/cv.png" alt-="coverletter example" width="300px"/>
  <img src="https://github.com/nidzov/nidzocv/blob/master/media/cvalt.png" alt-="coverletter example" width="300px"/>
</div>

## How to use

Fill main.tex, cvsidebar.tex and cvbody.tex with information and build it.

### Example for main information in main.tex

```latex
% \cvSetLanguage{german}
\cvSetLanguage{english}

\setFirstName{Firstname}
\setLastName{Lastname}
\setAddress{Street 1}
\setZipcode{12345}
\setCity{City}
\setEmail{firstname.lastname@mail.com}
\setPhone{+49 162 1234 567}

\setPicture{media/profilepic.png}
\setSignaturePicture{media/signature.png}

\setCompanyName{Company Name}
\setContactPerson{Contact HR Person\\}
\setCompanyAddress{Companystreet. 2}
\setCompanyZip{12345}
\setCompanyCity{City}
\setPosition{Applicationposition}

\setJobofferURL{Position on google.com,}
\setPositionId{Job ID 1234}
```
## Thanks

Big thank you to [opieters/limecv](https://github.com/opieters/limecv)
