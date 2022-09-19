# Nabebin Andrew

![Nabebin Andrew](https://github.com/N-bin-Andr/rsschool-cv/tree/gh-pages/img/n200round.png)

## Location: 

Minsk, Belarus.

## Contacts
- E-mail: n.bin.andr@gmail.com
- Twitter: @Nab_Andrey
- Facebook: Nabebin Andrew
- LinkIn: Andrew Nabebin
- Discord: Andrei Nabebin#2320

## In brief about myself

Despite the humanitarian profile of my main education, by nature I more prone to the exact sciences and technical disciplines. From a certain stage in my life, writing code has become a favorite hobby for me that I spend almost all my free time. I love to learn and experience new things. I do my best to turn my favorite hobby into my main profession.

## Goals:

Trainee or junior as the first step in Frontend

## Skills:

- HTML, CSS, JS (studying)
- Bootstrap (studying)
- Git, GitHub (studying)
- VBA VB6
- JAVA, FX (the basics) 
- Linux, Linux bash (the basics)
- VC code, Sublime text, JetBrains IntelliJ IDEA
- Figma
- Photoshop, Gimp (the basics)
- Blind 10-finger typing method (ru, en).
- Microsoft Office: Word, Excel, Outlook, Access (with VBA programming);

#### JS code example:
```
function isograms(str) {
  let arr = str.toLowerCase().split('');
  let result = true;
  arr.map((item, index) => {
    if (arr.indexOf(item, ++index) > 0) {
      result = false;
    }
  });
  return result;
}
```

#### VBA code example:
```
Public Function isLeapYear(dt As Date) As Boolean
Dim str As String
    If dt = 0 Then
        MsgBox Msg + "Zero is not a valid date!"
        Do While dt = 0
            str = InputBox("Enter the valid date: ", "date correction", DateTime.Date)
            dt = isDateValid(str)
        Loop
    End If
Dim tmpYear As Long
    tmpYear = DatePart("yyyy", dt, vbMonday, vbFirstJan1)
    numDayOfYear = 366 + (tmpYear Mod 4 <> 0 Or (tmpYear Mod 400 = 0 And tmpYear Mod 100 <> 0))
    If numDayOfYear <> 365 Then
        isLeapYear = True
    Else: isLeapYear = False
    End If
End Function

```

#### java code example:
```
//ОПРЕДЕЛЕНИЕ ПОЛА:
 @Override
    public String getDF(float  measurement, int step){
    /* определение диагностических коэффициентов */
        method[step][1]="НПВ";
        if (measurement > 0f) {
            switch (step) {
                case 0: {
                    method[step][0] = "Наибольшая длина кости в естественном положении (мм.)";
                    if (measurement <= 283f) method[step][1] = "+беск.";
                    else if (measurement > 353f) method[step][1] = "-беск";
                    else {
                        if (measurement > 283f & measurement <= 303f) method[step][1] = "+159";
                        else if (measurement > 303f & measurement <= 313f) method[step][1] = "+61";
                        else if (measurement > 313f & measurement <= 323f) method[step][1] = "+23";
                        else if (measurement > 323f & measurement <= 343f) method[step][1] = "-59";
                        else if (measurement > 343f & measurement <= 353f) method[step][1] = "-128";
                        df[step] = Integer.parseInt(method[step][1]);
                    }
                    break;}
                //... case 1 - 8 code here
                }
      return "ДК = "+method[step][1];
    }
}
```

## Experience.

### 2005 — 2021
 Developing software for Microsoft Office Applications with VBA.

### 2002 - 2003

Minsk City Clinical Oncologic Dispensary (Minsk, Belarus). Project: "Thyroid National Tissue Bank".
#### Responsibility:
- Participation in the development and creation of the electronic database "National Thyroid Tissue Bank".
- Testing and maintaining the pathological part of the database, selection of archival tissue.
- Video capture and digitization of video images for various nosoologies of thyroid pathology.

Project: "Thyroid telepathology and telemedicine".
#### Responsibility:
- Examination of surgical material of the thyroid gland;
- Determination of the pathological anatomical diagnosis of tumours.

## Education.

### 2022

1. "JavaScript/Front-end 2022Q3" (RS School) in training
2. "HTML, CSS, and Javascript for Web Developers" (Coursera Johns Hopkins university online course).

### 2021

1. "JS/FE Pre-School" (RS School).
2. "JavaScript/Front-end 2021Q1" (RS School).

### 2017

Oline JAVA courses (Интуит).

### 2005 - 2021

Developing software for Microsoft Office applications with VBA, VB6

### 2005

Belarusian Medical Academy of Post-Graduate Education (Minsk,
Belarus). Completed the course "Advanced Medical English".
Qualification: certificate.

### 1991 – 1997

Minsk State Medical Institute (Minsk, Belarus).
Qualification : Higher education diploma/

### 1987 September - 1988 May

Secondary Vocational Technical School №69 (Soligorsk, Belarus).
Qualification: Electrician (locksmith) on duty and on repair of equipment, 4 grade.

## Languages

* Russian (native)
* English (intermediate)
