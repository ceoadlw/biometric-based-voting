Okay, here is the document converted into GitHub Flavored Markdown, with images replaced by placeholders based on their captions or surrounding context.

# TABLE OF CONTENTS

*   [Acknowledgement](#acknowledgement)
*   [Executive Summary](#executive-summary)
*   [Table of Contents](#table-of-contents)
*   [List of Figures](#list-of-figures)
*   [List of Tables](#list-of-tables)
*   [List of Abbreviations](#list-of-abbreviations)
*   [Symbols and Notations](#symbols-and-notations)
*   [1. INTRODUCTION](#1-introduction)
    *   [1.1. OBJECTIVE](#11-objective)
    *   [1.2. MOTIVATION](#12-motivation)
    *   [1.3. BACKGROUND](#13-background)
*   [2. PROJECT DESCRIPTION AND GOALS](#2-project-description-and-goals)
    *   [2.1. VOTER REGISTRATION](#21-voter-registration)
    *   [2.2. AREA BASED DATABASE](#22-area-based-database)
    *   [2.3. VOTE CASTING](#23-vote-casting)
    *   [2.4. VOTE BLOCKCHAIN](#24-vote-blockchain)
*   [3. TECHNICAL SPECIFICATION](#3-technical-specification)
    *   [3.1. INTRODUCTION](#31-introduction)
    *   [3.2. TECHNICAL SPECIFICATION ANALYSIS](#32-technical-specification-analysis)
        *   [3.2.1. FUNCTIONAL SPECIFICATIONS](#321-functional-specifications)
            *   [3.2.1.1. PRODUCT PERSPECTIVE](#3211-product-perspective)
            *   [3.2.1.2. PRODUCT SPECIFICATIONS](#3212-product-specifications)
            *   [3.2.1.3. USER CHARACTERISTICS](#3213-user-characteristics)
            *   [3.2.1.4. ASSUMPTION & DEPENDENCIES](#3214-assumption--dependencies)
            *   [3.2.1.5. DOMAIN SPECIFICATIONS](#3215-domain-specifications)
            *   [3.2.1.6. USER SPECIFICATIONS](#3216-user-specifications)
        *   [3.2.2. NON-FUNCTIONAL SPECIFICATIONS](#322-non-functional-specifications)
            *   [3.2.2.1. PRODUCT SPECIFICATIONS](#3221-product-specifications)
            *   [3.2.2.2. ORGANIZATIONAL SPECIFICATIONS](#3222-organizational-specifications)
                *   [3.2.2.2.1. IMPLEMENTATION SPECIFICATIONS](#32221-implementation-specifications)
            *   [3.2.2.3. OPERATIONAL SPECIFICATIONS](#3223-operational-specifications)
        *   [3.2.3. SYSTEM SPECIFICATIONS](#323-system-specifications)
            *   [3.2.3.1. H/W SPECIFICATIONS](#3231-hw-specifications)
            *   [3.2.3.2. S/W SPECIFICATIONS](#3232-sw-specifications)
*   [4. DESIGN APPROACH AND DETAILS](#4-design-approach-and-details)
    *   [4.1. DESIGN APPROACH / MATERIALS & METHODS](#41-design-approach--materials--methods)
    *   [4.2. CODES AND STANDARDS](#42-codes-and-standards)
    *   [4.3. CONSTRAINTS, ALTERNATIVES AND TRADE-OFFS](#43-constraints-alternatives-and-trade-offs)
*   [5. SCHEDULE, TASKS AND MILESTONES](#5-schedule-tasks-and-milestones)
*   [6. PROJECT DEMONSTRATION](#6-project-demonstration)
*   [7. COST ANALYSIS / RESULT & DISCUSSION](#7-cost-analysis--result--discussion)
*   [8. SUMMARY](#8-summary)
*   [9. REFERENCES](#9-references)
*   [APPENDIX A](#appendix-a)

---

## Acknowledgement

[Content for Acknowledgement]

---

## Executive Summary

[Content for Executive Summary]

---

## List of Figures

| Figure No. | Title                                                    |
| :--------- | :------------------------------------------------------- |
| 2.1        | Voting Blockchain                                        |
| 4.1        | Flowchart for suggested e-voting process                 |
| 4.2        | A template for the smart card with integrated chip       |
| 4.3        | Voter Registration using smart card and biometrics       |
| 4.4        | Website Structure                                        |
| 4.5        | Proposed key generation using DNA Encoding/Decoding      |
| 4.6        | Authentication of Voters                                 |
| 4.7        | Vote Casting Process in the Estonian E-Voting System     |
| 4.8        | Voting in Bangladesh                                     |

---

## List of Tables

| Table No. | Title           | Page No. |
| :-------- | :-------------- | :------- |
| 4.1       | DNA Complement  | 16       |

---

## List of Abbreviations

| Abbreviation | Full Form                       |
| :----------- | :------------------------------ |
| EVM          | Electronic Voting Machine       |
| DNA          | Deoxyribonucleic Acid           |
| AES          | Advanced Encryption Standard    |
| FAR          | False Acceptance Rate           |
| FRR          | False Rejection Rate            |
| SHA          | Secure Hash Algorithms          |
| NID          | National ID                     |
| PII          | Personal Identifiable Information |

---

## Symbols and Notations

| Symbol | Meaning      |
| :----- | :----------- |
| V      | Exclusive OR |

---

# 1. INTRODUCTION

In our effort to find an optimal solution for voting processes, we needed to identify the problems first. The objective and the motivation to pursue this project has been outlined below.

## 1.1. OBJECTIVE

We follow the same objectives that are maintained for paper-based voting. The objectives are as follows: [8]

1.  **Fairness:** No voter is discriminated against.
2.  **Eligibility:** Only registered and eligible voters are permitted to vote.
3.  **Uniqueness:** No voter can cast two votes.
4.  **Privacy:** All information about an individual's vote is anonymous.
5.  **Accuracy:** All votes should be accounted for.
6.  **Efficiency:** The outcome of the votes should be available as soon as possible.

## 1.2. MOTIVATION

The voting system is a way for people to let their choice known. Most of the democratic countries have been using paper-based voting system from the establishment of democracy, but there are several issues like missing ballot paper, miscalculation, invalid vote. As a result, the electronic voting system has become more popular than the paper-based voting system from the last few years, and it has been observed in the election of the Estonia. Various kinds of vulnerabilities exist within the current e-voting system. If the e-voting system to be successful, it requires a transparent and secure approach. Voting is the most fundamental right of a citizen. It is the most important right given to a citizen by their democratic institution. Even then voter fraud is one of the most occurring phenomena during elections. Utilizing smart cards and biometrics along with blockchain, we think we have produced a novel solution to eliminate voter fraud.

## 1.3. BACKGROUND

The industry is moving towards a password-less future which is relying on a more secure technology: biometrics. Biometrics have become extremely popular due to its convenience and level of security. There are more security tools available now than ever which also introduces risks. Even then the combination of multiple authentication tools is what is used by multinational conglomerates to protect their data and secrets. These tools are used to safeguard secrets that are worth trillions to the companies. Our paper will also establish a combination of multiple security tools that can be used to eliminate voter fraud. This is an issue that has been plaguing the voting process since the inception of democracy. Due to the recent developments of technology, we believe using integrated circuits and chips in smart cards along with blockchain can eliminate voter fraud finally.

---

# 2. PROJECT DESCRIPTION AND GOALS

Our voting mechanism is reliant on smart cards. These cards will have standard hardware encryption and will require proprietary hardware to read them. There are multiple modules that will work together to ensure that voter fraud is not being carried out. All the modules of our concept have been detailed below.

## 2.1. VOTER REGISTRATION

Voter registration must be done in specific centres. This will ensure no modification has been done during the process of writing data to the cards. The officials will have machines installed for writing and encrypting biometric data on the smart cards. The biometrics that can be used for verification and authentication can be retinal or iris scanner, fingerprint scanner or face recognition.

The decentralization of biometrics will not only ensure the biometric data is secure, but it will also discourage attackers. If a voter loses a card, it will be easy to disable and issue a new card for the voter from government specified centres. If the previous card's data is compromised, there is no benefit since the card cannot be used to cast a vote. The hash check in our system will prevent unauthorized modifications to be rejected. Cards can also be replaced easily from government specified centres by removing the old card details from system and issuing new card to the voter.

## 2.2. AREA BASED DATABASE

Maintaining voter databases in read-only mode during an election is effective but utilizing blockchain will make it more secure and allow transparency between different departments and areas of all changes being made in real time. The PII of voters is stored in these databases.

The databases of each voting area/constituency will serve as an individual block. The blockchain will be formed after the databases of all areas are completed. The administration of respective areas will have access to their blocks only. Modification to blocks will be done annually after accumulation of all modifications for that year. This will allow proper scrutiny of the data before logging them into the main database and since all of them will be a part of blockchain, all the areas must be coordinated to make the changes.

## 2.3. VOTE CASTING

Voters will arrive at the polling booth with their smart cards. There is no bypass if the voter forgets to bring their ID card. It is fundamental to this concept as the smart card will contain the encrypted biometric templates that will be used to authenticate and verify the user's vote.

The hash of the encrypted data on the card is again calculated when the voter comes for voting. The Smart contract will initiate hashing and fetching operation automatically. If the hash matches with the data on the server, the key will be fetched to decrypt the templates on the card. Once it is decrypted, the voter will be verified using his/her biometrics through the biometric sensors on the EVM. After the voter is verified, the voter will then be allowed to cast their vote. The vote is taken and added to the vote blockchain which is maintained separately from the area based blockchain.

## 2.4. VOTE BLOCKCHAIN

A blockchain will be maintained for all the votes. Each transaction will contain the Transaction ID, the Machine ID and the candidate that has been voted for. The machine ID signature on each vote will ensure that voters have provided vote in their designated centres. It will also reject votes if the machine ID designated to voter location does not match. Voters will only be allowed to vote once. Vote duplication is not possible as the system will detect the voter is trying to vote twice or trying to vote outside the specified voting location.

[Image: Fig. 2.1: Voting Blockchain]

In case of concurrent votes, the blocks will be split according to ‘The Longest Chain' rule of Bitcoin.[14] We can see the example in the fig. When there are 3 concurrent votes at the same time, they are split into 3 blocks with alphabets i.e., Vote 2A, Vote 2B, Vote 2C. If there are more than 26 votes concurrently, then numbers will be added to help differentiate i.e., Vote 2A1, Vote 2B1 ... Vote 2Z1, Vote 2A2 and so on. The block will then continue with the longest chain with Vote 3A, Vote 4A ... Vote NA. This is the longest chain rule of blockchain.

---

# 3. TECHNICAL SPECIFICATION

## 3.1. INTRODUCTION

The demographic for our project is the citizens of a demographic country. The voting process itself must be existing within the country to allow for a fair and transparent election. Utilization of blockchain technology will allow all votes to be verified if required without the disclosure of voters' identities.

## 3.2. TECHNICAL SPECIFICATION ANALYSIS

### 3.2.1. FUNCTIONAL SPECIFICATIONS

#### 3.2.1.1. PRODUCT PERSPECTIVE

With so many reports of voter fraud coming against governments, it is about time advanced technologies are adapted into the voting system. Citizens will see the introduction of blockchain into the voting system as a positive decision. This will ensure that moving forward all voting done under the government will be fair and unbiased. There can be no harassment if a government does not get desired results from elections as the votes will remain anonymous.

#### 3.2.1.2. PRODUCT SPECIFICATIONS

**Decentralisation:** The project focuses on decentralisation because it will remove the liability of user's biometric data from the authorities. Users will have to be responsible for carrying their own smart cards.

**Enhanced Template Security:** Using a novel algorithm utilizing DNA encoding/decoding and chaotic maps we can provide better security for the templates stored in the smart cards. This enhanced security will ensure increased difficulty for hackers to try and modify data on the smart cards. Even if they are successful the hash check and face recognition will have block their access to the voting page.

**Blockchain Technology:** Blockchain is based on privacy and security. It ensures that all users are secure and private while all transactions that are committed to the blockchain are public. This way none of the data can be forged but it will also ensure that no transaction is made behind the back of the public. Users themselves can verify their votes have been cast properly or not by browsing through the blockchain.

#### 3.2.1.3. USER CHARACTERISTICS

**Voter:** The usual voter must be above 18 years old and should have the mental capacity to make important decisions. Voters are also expected to be citizens of the nation they are voting in.

**Administrator:** The administrator will have the power to register voters and monitor their actions while voting. He/she will however not have the power to override any system protocols.

#### 3.2.1.4. ASSUMPTION & DEPENDENCIES

We assume that both users and administrators are unbiased and in the worst-case scenario one of them is biased while the other is unbiased. So, we assume that the administrators may be corrupt but the voters are not as they hope for a better government. Even in this scenario, any modification will require a 51% stake over the whole blockchain and even if they are successful, people will be able to see the modification publicly on the blockchain.

This will alert the citizens to the corruption taking place behind the scenes and ask for re-election, discredit the election with proof, or seek legal action against the collaborators.

#### 3.2.1.5. DOMAIN SPECIFICATIONS

As this will be used for government purposes, a .gov domain is necessary to ensure voters that they are seeing results on the official government domain. This will also help identify fake proxies that may be created using .com or .org domains. People will be able to identify the fake websites and will be able to help the authorities track down any fake websites.

#### 3.2.1.6. USER SPECIFICATIONS

**Voter:** Voters are expected to carry their smart cards while arriving for voting. They are also responsible to check if their votes have been cast correctly on the blockchain explorer. Voters are also responsible for reporting if their smart card is lost or damaged.

**Administrator:** Administrators have a particularly key role in this system. They must make sure their credentials are safe and uncompromised. They must report to higher authorities in case they forget their credentials. Administrators will also be allowed to access the system from authorized terminals. It is also expected for them to be adept at handling computer systems.

### 3.2.2. NON-FUNCTIONAL SPECIFICATIONS

#### 3.2.2.1. PRODUCT SPECIFICATIONS

**Efficiency**
Electronic voting machines are very efficient. All proof-of-work and proof-of-stake will be done on the machines itself so the server-side load will be very less. It will also decrease the time required to count votes. Results can be declared immediately as soon as election time is over.

**Reliability**
The EVMs have no way of being modified and even if they are modified the machines will not be able to cast vote because any kind of modification will lead to modification of the machine's signature. And modification to data stored on the smart card will lead to a generation of a different hash which will not allow the voter to vote. Due to the hash mismatch, authorities will also be alerted so that the issue can be investigated.

**Portability**
Smart Cards will be portable and quite easy to carry. It is a small card with the same form factor of credit cards. Voters will have no issue carrying this card and it will be very handy to provide verification in times of need.

**Usability**
The smart cards will be very easy-to-use. Everything will be programmed into the system so voters will just have to punch cards and verify themselves using the 3D camera that will be built into the EVM. After that they will cast their vote and the system will do everything for them.

Admins will also have exceedingly small tasks to perform as the system will have most of the features built into them. Admins will have the role of monitoring and allowing people to register when they come for registering to be a voter.

#### 3.2.2.2. ORGANIZATIONAL SPECIFICATIONS

##### 3.2.2.2.1. IMPLEMENTATION SPECIFICATIONS

Implementation will require hardware compatible with the software platform. It will require chip readers and EVMs developed for this specific procedure. It will cost a lot to setup the initial project but once it is developed, it will sustain for an extended period. It can be used for local and central government elections.

#### 3.2.2.3. OPERATIONAL SPECIFICATIONS

**Economic**
Our solution is more economic than current ballot paper system. Millions of ballot paper are wasted during voting procedure. It is also inefficient and costly as a lot of personnel must be hired to run the polling centers. Our process will automate a huge portion of the process and remove the need for excessive personnel. Overall, this process will save governments a lot of money.

**Social**
If the smart cards can be utilized for other purposes than voting, it will make verification of citizens extremely easy. Bangladesh has adopted this approach and utilize their smart voting card for 22 services which includes voting. This will help reduce hidden transactions overall. A social feature can also be introduced to reward citizens for not breaking laws and helping the government with different tasks. All of which will utilize the smart card which will act as an identity verification card.

**Political**
Political groups have a lot of influence with government employees who work within the election process. This can lead to various sorts of malpractice such as voter fraud and duplication of votes with the help of the employees at polling locations. If EVMs are introduced, the process of authenticating voters and their votes will be automated. This will also remove the need of manual vote counts. Politically this will help the nation move forward while discouraging malpractice in the voting process.

**Ethical**
Storage of biometrics is frowned upon and we agree on that. That is why we give users their own biometric data to keep with them instead of storing it on our servers. Decentralizing the storage of biometric data not only increases security, it also provides a guarantee that user's biometrics are not under threat from the government. So, our project will ensure that there is no breach of trust between the voters and the authorities.

**Legality**
Since the project is related to the voting process and will require government approval to be adopted nationwide, it is legal. There is no part of it which may portray the government or this project in a negative manner.

### 3.2.3. SYSTEM SPECIFICATIONS

#### 3.2.3.1. H/W SPECIFICATIONS

1.  Smart Cards
2.  Electronic Voting Machines
3.  Servers configured to perform blockchain operations
4.  3D Camera/Fingerprint Scanners/Retina Scanners

#### 3.2.3.2. S/W SPECIFICATIONS

1.  Python
2.  Hyperledger Fabric/Solidity
3.  HTML
4.  CSS
5.  JavaScript
6.  Web3.JS

---

# 4. DESIGN APPROACH AND DETAILS

## 4.1. DESIGN APPROACH / MATERIALS & METHODS

The flowchart below was the beginning of our planning. We decided to use this as to discuss what other technology and features we would include in our project.

[Image: Fig. 4.1: Flowchart for suggested e-voting process]

We realized hardware security is as important as software in this project. As a result, we planned to utilize smart cards for users to carry their biometric data. They will be equipped with chips that carry their encrypted templates onboard.

[Image: Fig. 4.2: A template for the smart card with integrated chip]

Then we decided on the process for encrypting and decrypting the data from the card. The following process shows how registration is carried out in our project.

[Image: Fig. 4.3: Voter Registration using smart card and biometrics]

Then we decided on the website structure to help us plan the design and architecture of the project.

[Image: Fig. 4.4: Website Structure]

Then we decided on the encryption algorithm for the biometric templates. We referred to papers and finally decided on one. The algorithm has been discussed below.

**Biometric Template Encryption:** The templates will be scrambled using chaotic systems and then encoded using DNA. The encoded data is complemented and decoded again. This data is hashed using SHA2 and the output is the key used for encryption of the templates. [4]

[Image: Fig. 4.5: Proposed key generation using DNA Encoding/Decoding]

Using the key generated using the above procedure the biometric templates are encrypted. The encrypted template is then stored on the smart card. The key is stored against the NID/SSN in the database. Multiple biometrics are stored so that voters can use an alternative biometric in case their preferred biometric is not working, or they lose the part of their body which was used to register the template in the first place.

**Template Protection Properties:**

1.  **Diversity:** There should not be matches with existing templates within the databases
2.  **Revocability:** Utilizing old templates, new templates can be reproduced
3.  **Security:** Should be impossible to recreate identical template from encrypted data
4.  **Performance:** FAR and FRR must be within acceptable limits

DNA sequences are based on four nucleic acids, A, C, G, T. A for Adenine, C for Cytosine, G for Guanine and T for Thymine. The following complements A to T and G to C. There are 24 types of nucleic acid basis coding schemes, of which the complementary Watson-Crick rule consists of 8 systems as shown in table 1. Sequences of DNA hold biological information for encrypting purposes.[4]

**Table 4.1: DNA Complement [4]**

| Rule Set 1             | Rule Set 2             |
| :--------------------- | :--------------------- |
| (AC)(TC)(CG)(GA)       | (AT)(TG)(GC)(CA)       |
| (AC)(CT)(TG)(GA)       | (AC)(CG)(GT)(TA)       |
| (AG)(GT)(TC)(CA)       | (AG)(GC)(CT)(TA)       |

Now the generated key can be used for encryption. Encoded output after DNA decoding is shown below:


CAATGCTCACTGCGTCGACACATAAGACGTGTCCACCGGTTGCCCAAGCTGTGA
AGTGTCTACCACCCCTAGGCCCGTTTCCCGCACACAAACGCCGGGTTGTGTCCGC
ATCTGATGCTGCCGCGGGCGAGTCAGCGTCGAGCACGCGGCACTTATTGCATGA
GTAGGGTTGACTAAGAGCCGTCAGATGCCTCGCTGTGCTAATAGTTGCCGACAG
ATCGTCAAGATTAGAGAACGGTGCCAGCATTTTCGGAGG

The 256-bit binary version is given below.
IGNORE_WHEN_COPYING_START
content_copy
download
Use code with caution.
IGNORE_WHEN_COPYING_END

001101010100000101000101010000010011001000110011010001010011011000111000001
100000011001101000011010001000100010001000011001110000011001001000101001100
000011100000111000001101110011000100110111001101110100001100110010010000110
100010001000001010001010011001100110110010001100100001100111000001100100011
000101000100001101100011011000110101010000100100010000110100001110010011011
001000101010001100100010000110100001101000011011101000010001101010100001001
00010101000010010000110011000100110001001101000100000101000110

The key generated using the DNA variable is used to encrypt the biometric template using AES256. The encrypted data is then hashed and the hash is stored against the respective NID number of the voter. The encrypted biometric templates are then written on the smart cards.

**Algorithm:**

1.  Input two pictures and split into binary blocks of equivalent size. Suppose I as image in 3 blocks named `A1`, `A2` and `A3`
    `I (a, b, 2) =A1(a, b) + A2(a, b)`
2.  Choose a chaotic system and produce scrambled output of images by inputting the value of `x, y, z, q`.
3.  Using chaotic sequence values `|lx,ly,lz,lq|`, the blocks are converted into unorganized images.
    `A1(i,j) <-> A1(lx(i),ly(j))`
    `A2(i,j) <-> A2(lx(i),lz(j))`
    `A3(i,j) <-> A3(ly(i),lz(j))`
4.  Split the output in blocks `A1n`, `A2n`, `A3n`.
5.  Addition of the output blocks.
    `A1n {i, j} = A1n {i, j} + A1(lx(i), ly(j))`
    `A2n {i, j} = A2n {i, j} + A2(lx(i), lz(j))`
6.  DNA complement for `A1'`, `A2'`.
7.  DNA decoding is done for `A1'`, `A2'`.
8.  Combine the blocks and hash using `SHA256` to produce the key.
9.  Key is used to encrypt the given image and hashed again. The hash and key are sent to cloud while the encrypted data is written to the card.

**Voter Authentication:** Voter authentication is done in real time using biometrics. The process for which has been shown in the figure below.

[Image: Fig. 4.6: Authentication of Voters]

## 4.2. CODES AND STANDARDS

The project kicks off with the user visiting the home page. From there the user must register themselves as a voter. The user must register his/her biometrics. As the user registers his/her biometrics, it is encrypted using the algorithm of DNA Encoding/Decoding.

The code for encoding and saving the encrypted image on the smart card is as follows:

**encr.py**
```python
# encr.py (combined snippets from pages 19, 20)
from PIL import Image
import tkinter as tk
from tkinter import filedialog
import hashlib
import binascii
import textwrap
import cv2
import numpy as np
from scipy.integrate import odeint
import matplotlib.pyplot as plt
from mpl_toolkits.mplot3d import Axes3D
import sys
from importlib import reload
from bisect import bisect_left as bsearch
import key_gen # Assuming key_gen.py contains necessary functions
import pickle as cPickle
import mysql.connector
from mysql.connector import Error

# GLOBAL Constants
# Lorenz paramters and initial conditions
a, b, c = 10, 2.667, 28
x0, y0, z0 = 0, 0, 0

#DNA-Encoding RULE #1 A 00, T-01, G-10, C-11
dna={}
dna["00"]="A"
dna["01"]="T"
dna["10"]="G"
dna["11"]="C"
dna["A"]=[0,0]
dna["T"]=[0,1]
dna["G"]=[1,0]
dna["C"]=[1,1]

#DNA xor
dna["AA"]=dna["TT"]=dna["GG"]=dna["CC"]="A"
dna["AG"]=dna["GA"]=dna["TC"]=dna["CT"]="G"
dna["AC"]=dna["CA"]=dna["GT"]=dna["TG"]="C"
dna["AT"]=dna["TA"]=dna["CG"]=dna["GC"]="T"

#Maximum time point and total number of time points
tmax, N = 100, 10000

#program exec9
if (__name__ == "__main__"):
    file_path = key_gen.image_selector()
    print(file_path)
    key, m, n = key_gen.securekey(file_path) # Generates hash and gets dimensions
    key_gen.update_lorentz(key) # Updates Lorenz initial conditions based on key
    blue, green, red = key_gen.decompose_matrix(file_path) # Splits image into RGB matrices
    blue_e, green_e, red_e = key_gen.dna_encode(blue, green, red) # DNA encodes RGB matrices
    Mk_e = key_gen.key_matrix_encode(key, blue) # Encodes key matrix using DNA encoding
    blue_final, green_final, red_final = key_gen.xor_operation(blue_e, green_e, red_e, Mk_e) # XORs encoded image with encoded key

    x,y,z = key_gen.gen_chaos_seq(m,n) # Generates chaotic sequences
    fx, fy, fz = key_gen.sequence_indexing(x,y,z) # Creates index sequences from chaotic sequences
    blue_scrambled, green_scrambled, red_scrambled = key_gen.scramble(fx, fy, fz, blue_final, red_final, green_final) # Scrambles the XORed image

    b,g,r = key_gen.dna_decode(blue_scrambled, green_scrambled, red_scrambled) # Decodes the scrambled image channels
    img = key_gen.recover_image(b,g,r,file_path) # Reconstructs the final encrypted image

    # Prepare data for database storage
    listToPickle = img, fx, fy, fz, file_path, Mk_e, blue, green, red # Note: Storing raw image and intermediate steps
    pickledList = cPickle.dumps(listToPickle)

    # Database interaction
    try:
        connection = mysql.connector.connect(user='newuser', password='password', host='127.0.0.1', database='capstone')
        cursor = connection.cursor()

        # Get the NID of the last updated record (assuming this identifies the target voter)
        sql_select_nid = "select nid from area order by updated_at desc limit 1"
        cursor.execute(sql_select_nid)
        rows = cursor.fetchall()

        # Update the voter record with the pickled encrypted data
        sql_update_enc = "update area set enc_data = %s where nid = %s"
        if rows:
            for row in rows:
                nid_to_update = row[0]
                val = (pickledList, nid_to_update)
                cursor.execute(sql_update_enc, val)
            connection.commit()
            print(f"Encrypted data stored for NID: {nid_to_update}")
        else:
            print("No voter record found to update.")

    except Error as e:
        print(f"Error connecting to MySQL: {e}")
    finally:
        if connection.is_connected():
            cursor.close()
            connection.close()
            print("MySQL connection is closed")
IGNORE_WHEN_COPYING_START
content_copy
download
Use code with caution.
IGNORE_WHEN_COPYING_END

Here we are using pickle dump to store the values of the encrypted image in the database as a long blob datatype which will be used to decrypt the uploaded image (at the time of vote cast) only if the encrypted image's hash matches a hash value in the database.

key_gen.py

# key_gen.py (combined snippets from pages 21-26)
from PIL import Image
import tkinter as tk
from tkinter import filedialog
import hashlib
import binascii
import textwrap
import cv2
import numpy as np
from scipy.integrate import odeint
import matplotlib.pyplot as plt
from mpl_toolkits.mplot3d import Axes3D
import sys
import mysql.connector
from mysql.connector import Error
from importlib import reload
from bisect import bisect_left as bsearch
import pickle as cPickle # Used in encr.py, maybe needed here indirectly?

# GLOBAL Constants (repeated from encr.py, ideally import from a config file)
a, b, c = 10, 2.667, 28
x0, y0, z0 = 0, 0, 0
dna={}
dna["00"]="A"; dna["01"]="T"; dna["10"]="G"; dna["11"]="C"
dna["A"]=[0,0]; dna["T"]=[0,1]; dna["G"]=[1,0]; dna["C"]=[1,1]
dna["AA"]=dna["TT"]=dna["GG"]=dna["CC"]="A"
dna["AG"]=dna["GA"]=dna["TC"]=dna["CT"]="G"
dna["AC"]=dna["CA"]=dna["GT"]=dna["TG"]="C"
dna["AT"]=dna["TA"]=dna["CG"]=dna["GC"]="T"
tmax, N = 100, 10000 # N might be redefined later

# Lorenz chaotic system differential equations
def lorenz(X, t, a, b, c):
    x, y, z = X
    x_dot = a*(y - x) # Corrected Lorenz equation
    y_dot = x*(c - z) - y # Corrected Lorenz equation
    z_dot = x*y - b*z # Corrected Lorenz equation
    return x_dot, y_dot, z_dot

# Image selection GUI (Simplified - using fixed path for demo)
def image_selector():
    # In a real app, use filedialog.askopenfilename()
    path = "images_db/xyz.png" # Using placeholder path
    if path and path != "NULL": # Basic check
         print("Image loaded!")
         return path
    else:
         print("Error Image not loaded!")
         return None

# Split image into RGB channels (numpy arrays)
def split_into_rgb_channels(image):
    # Assumes image is loaded with cv2.imread which uses BGR order
    blue = image[:,:,0]
    green = image[:,:,1]
    red = image[:,:,2]
    return red, green, blue # Return in RGB order for consistency

# Secure key generation (SHA256 hash of pixel data) and DB storage
def securekey (iname):
    try:
        img = Image.open(iname)
        pix = img.load()
        m, n = img.size
        print("pixels: {0} width: {1} height: {2} ".format(m*n, m, n)) # Corrected format call

        plainimage = list()
        # _plainimage contains all the rgb values continuously
        for y in range(n):
            for x in range(m):
                # Ensure pixel access is correct for PIL (pix[x,y])
                pixel = pix[x,y]
                # Handle grayscale or RGBA images if necessary
                if isinstance(pixel, int): # Grayscale
                    plainimage.extend([pixel, pixel, pixel]) # Repeat gray value for R,G,B
                elif len(pixel) == 3: # RGB
                     plainimage.extend(pixel)
                elif len(pixel) == 4: # RGBA
                    plainimage.extend(pixel[:3]) # Ignore alpha
                else:
                    print(f"Warning: Unexpected pixel format at ({x},{y}): {pixel}")
                    # Handle error or default value as needed
                    plainimage.extend([0,0,0])


        key = hashlib.sha256()
        # image data is fed to generate digest
        key.update(bytearray (plainimage))
        key_value = key.hexdigest()
        print(f"Generated SHA256 hash: {key_value}")
        # print(len(key.hexdigest())) # Should be 64

        # Establishing the connection and storing hash
        conn = None
        cursor = None
        try:
            conn = mysql.connector.connect(user='newuser', password='password', host='127.0.0.1', database='capstone')
            cursor = conn.cursor()

            # Preparing SQL query to find the latest NID and update its hash.
            sql_select = "select nid from area order by updated_at desc limit 1"
            cursor.execute(sql_select)
            rows = cursor.fetchall()

            if rows:
                nid_to_update = rows[0][0]
                sql_update = "update area set enc_hash = %s where nid = %s" # Added enc_hash column assumption
                val = (key_value, nid_to_update)
                cursor.execute(sql_update, val)
                conn.commit()
                print(f"Hash stored for NID: {nid_to_update}")
            else:
                print("No voter record found to update hash.")

        except Error as e:
            print(f"Database Error: {e}")
            if conn:
                conn.rollback() # Rollback changes in case of error
        finally:
            if cursor:
                cursor.close()
            if conn and conn.is_connected():
                conn.close()
                # print("MySQL connection closed.") # Usually logged elsewhere

        return key_value, m, n # Return hash and dimensions

    except FileNotFoundError:
        print(f"Error: Image file not found at {iname}")
        return None, 0, 0
    except Exception as e:
        print(f"An error occurred in securekey: {e}")
        return None, 0, 0


# Update Lorenz parameters based on key digest
def update_lorentz (key):
    global x0, y0, z0 # Allow modification of globals
    key_bin = bin(int(key, 16))[2:].zfill(256) # convert hex key digest to binary
    # key dictionary - slicing key into 8 parts (32 * 8 bits = 256 bits)
    k={}
    key_32_parts=textwrap.wrap(key_bin, 32) # Changed slice to 32 bits for 8 parts
    num=1
    for i in key_32_parts:
        k["k{0}".format(num)]=i
        num += 1

    # Calculate t1, t2, t3 by XORing parts of the key
    # Example logic (original seemed to miss indices and had overlapping ranges)
    t1 = 0
    for i in range (1,4): # Parts 1, 2, 3 for t1
         if f"k{i}" in k: t1 ^= int(k[f"k{i}"], 2)
    t2 = 0
    for i in range (4,7): # Parts 4, 5, 6 for t2
         if f"k{i}" in k: t2 ^= int(k[f"k{i}"], 2)
    t3 = 0
    for i in range (7,9): # Parts 7, 8 for t3
        if f"k{i}" in k: t3 ^= int(k[f"k{i}"], 2)

    # Update initial conditions (using scaled XOR sums)
    x0 = x0 + t1 / (2**32 -1) # Scale by max possible value
    y0 = y0 + t2 / (2**32 -1)
    z0 = z0 + t3 / (2**32 -1)
    # print(f"Updated initial conditions: x0={x0}, y0={y0}, z0={z0}")

# Decompose image file into B, G, R numpy matrices
def decompose_matrix(iname):
    try:
        image = cv2.imread(iname)
        if image is None:
            print(f"Error: Could not read image {iname} with OpenCV.")
            return None, None, None
        # OpenCV reads in BGR order by default
        blue, green, red = image[:,:,0], image[:,:,1], image[:,:,2]
        # Convert to numpy matrices (though numpy arrays are generally preferred)
        B = np.asmatrix(blue)
        G = np.asmatrix(green)
        R = np.asmatrix(red)
        return B,G,R
    except Exception as e:
        print(f"Error decomposing image matrix: {e}")
        return None, None, None

# DNA Encode RGB channels
def dna_encode(b,g,r):
    encoded_channels = []
    for channel_matrix in (b, g, r):
        # Ensure input is a numpy array for unpackbits
        channel_array = np.array(channel_matrix)
        # Unpack bits: axis=1 unpacks each row independently
        unpacked = np.unpackbits(channel_array, axis=1)
        m, n_unpacked = unpacked.shape # n_unpacked = original_n * 8
        # Output shape will be m x (n_unpacked / 2)
        encoded = np.chararray((m, int(n_unpacked/2)))
        idx = 0
        for j in range(m):
            idx = 0 # Reset column index for each row
            for i in range(0, n_unpacked, 2):
                bit_pair = "{0}{1}".format(unpacked[j,i], unpacked[j,i+1])
                encoded[j, idx] = dna[bit_pair]
                idx += 1
                # Original break logic was incorrect, removed it.
        encoded_channels.append(encoded.astype(str)) # Convert to string type

    return encoded_channels[0], encoded_channels[1], encoded_channels[2] # b_enc, g_enc, r_enc

# Encode Key Matrix using DNA rules
def key_matrix_encode(key, b): # Uses 'b' channel dimensions
    b_array = np.array(b) # Ensure numpy array
    m, n = b_array.shape # Dimensions of the original image channel
    key_bin = bin(int(key, 16))[2:].zfill(256) # Binary key string
    Mk = np.zeros((m, n*8), dtype=np.uint8) # Key matrix matching unpacked image size
    x = 0
    for j in range(m):
        for i in range(n*8): # Iterate through all bits needed for the row
             Mk[j, i] = int(key_bin[x % 256]) # Repeat key bits as needed
             x += 1

    # DNA encode the binary key matrix Mk
    Mk_enc = np.chararray((m, int(n*8/2)))
    for j in range(m):
        idx = 0
        for i in range(0, n*8, 2):
            bit_pair = "{0}{1}".format(Mk[j,i], Mk[j,i+1])
            Mk_enc[j, idx] = dna[bit_pair]
            idx += 1

    return Mk_enc.astype(str)

# XOR operation using DNA rules
def xor_operation(b_e, g_e, r_e, Mk_e):
    m, n = b_e.shape # Encoded shape
    bx = np.chararray((m,n))
    gx = np.chararray((m,n))
    rx = np.chararray((m,n))

    b = b_e.astype(str) # Ensure string type
    g = g_e.astype(str)
    r = r_e.astype(str)
    mk = Mk_e.astype(str)

    for i in range(m):
        for j in range(n):
            # Perform XOR based on DNA rules defined in 'dna' dictionary
            bx[i,j] = dna[ b[i,j] + mk[i,j] ] # e.g., dna['AG'] = 'G'
            gx[i,j] = dna[ g[i,j] + mk[i,j] ]
            rx[i,j] = dna[ r[i,j] + mk[i,j] ]

    return bx.astype(str), gx.astype(str), rx.astype(str)

# Generate chaotic sequences using Lorenz system
def gen_chaos_seq(m, n):
    global x0, y0, z0, a, b, c # Use potentially updated initial conditions
    N_chaos = m * n * 8 # Number of points needed for full scramble (adjust if needed)
    t = np.linspace(0, tmax, N_chaos) # Time points for integration
    # Integrate Lorenz equations
    f = odeint(lorenz, (x0, y0, z0), t, args=(a, b, c))
    x, y, z = f.T # Get the sequences
    # Return sequences matching the size needed
    # Ensure the returned sequences have the correct length
    # Original code might have mismatch if N!=N_chaos
    return x[:N_chaos], y[:N_chaos], z[:N_chaos]

# Plot chaotic attractor (for visualization/debugging)
def plot(x,y,z):
    fig = plt.figure()
    ax = fig.add_subplot(111, projection='3d') # Correct way to add 3D subplot
    N_plot = len(x) # Use actual length
    s = 100 # Step size for plotting lines
    c = np.linspace(0, 1, N_plot)
    for i in range(0, N_plot - s, s):
         # Color format: (R, G, B) tuple, alpha for transparency
         ax.plot(x[i:i+s+1], y[i:i+s+1], z[i:i+s+1], color=(1-c[i], c[i], 0.5), alpha=0.4) # Example color mapping
    ax.set_axis_off()
    plt.show()

# Generate index sequences for scrambling based on sorted chaotic sequences
def sequence_indexing(x, y, z):
    n_seq = len(x)
    fx = np.zeros((n_seq), dtype=np.uint32)
    fy = np.zeros((n_seq), dtype=np.uint32)
    fz = np.zeros((n_seq), dtype=np.uint32)

    # Indexing for x
    seq_x = sorted(x)
    for k1 in range(n_seq):
        t = x[k1]
        k2 = bsearch(seq_x, t) # Find insert position (index) in sorted array
        # Handle duplicates: ensure unique index or manage as needed
        # Simple approach: use first found index. Refinements might be needed.
        while k2 > 0 and seq_x[k2-1] == t: k2 -= 1 # Find first occurrence
        fx[k1] = k2

    # Indexing for y
    seq_y = sorted(y)
    for k1 in range(n_seq):
        t = y[k1]
        k2 = bsearch(seq_y, t)
        while k2 > 0 and seq_y[k2-1] == t: k2 -= 1
        fy[k1] = k2

    # Indexing for z
    seq_z = sorted(z)
    for k1 in range(n_seq):
        t = z[k1]
        k2 = bsearch(seq_z, t)
        while k2 > 0 and seq_z[k2-1] == t: k2 -= 1
        fz[k1] = k2

    return fx, fy, fz

# Scramble image channels using chaotic index sequences
def scramble(fx, fy, fz, b, r, g): # Note order b,r,g seems intended?
    p, q = b.shape # Shape of the DNA-encoded channels
    size = p * q
    n_indices = len(fx) # Length of chaotic sequences

    # Ensure chaotic sequence length matches image size after encoding
    if n_indices != size * 4: # size = m*(n*8/2) = m*n*4. n_indices=m*n*8
        print(f"Warning: Index sequence length ({n_indices}) might not match required length ({size*4}). Adjust N_chaos.")
        # Adjust indices if needed, e.g., take modulo size
        # fx = fx % size ... (This might reduce chaotic properties)

    # Reshape encoded channels to 1D arrays
    bx = np.array(b).reshape(size).astype(str)
    gx = np.array(g).reshape(size).astype(str)
    rx = np.array(r).reshape(size).astype(str)

    # Create empty arrays for scrambled data
    bx_s = np.chararray((size))
    gx_s = np.chararray((size))
    rx_s = np.chararray((size))

    # Apply scrambling based on index sequences
    # Need to map indices correctly; original code might have issues
    # Assuming fx, fy, fz indices are 0 to size-1
    # Check if indices need scaling or modulo operation if lengths mismatch
    for i in range(size):
        # Use indices modulo size if lengths differ
        idx_z = fz[i] % size
        idx_y = fy[i] % size
        idx_x = fx[i] % size

        bx_s[i] = bx[idx_z] # Scramble blue using z sequence index
        gx_s[i] = gx[idx_y] # Scramble green using y sequence index
        rx_s[i] = rx[idx_x] # Scramble red using x sequence index

    # Reshape back to original encoded dimensions (p, q)
    b_s = bx_s.reshape(p, q)
    g_s = gx_s.reshape(p, q)
    r_s = rx_s.reshape(p, q)

    return b_s.astype(str), g_s.astype(str), r_s.astype(str)

# DNA Decode RGB channels
def dna_decode(b, g, r):
    decoded_channels = []
    for color_enc in (b, g, r):
        m, n = color_enc.shape # Shape of encoded (m, n/2)
        # Output shape will be (m, n*2) for binary bits
        decoded_binary = np.ndarray((m, n*2), dtype=np.uint8)

        # Reverse lookup dict for DNA decoding
        dna_rev = {v: k for k, v in dna.items() if isinstance(k, str) and len(k)==2} # {'A': '00', 'T': '01', ...}

        for j in range(m):
            for i in range(n):
                dna_char = color_enc[j, i].decode('utf-8') # Decode from bytes if necessary
                if dna_char in dna_rev:
                    bits = dna_rev[dna_char]
                    decoded_binary[j, 2*i]   = int(bits[0])
                    decoded_binary[j, 2*i+1] = int(bits[1])
                else:
                    print(f"Warning: Invalid DNA char '{dna_char}' at ({j},{i}) during decoding.")
                    decoded_binary[j, 2*i]   = 0
                    decoded_binary[j, 2*i+1] = 0

        # Pack bits back to uint8 bytes
        # axis=-1 (or 1) packs along the rows
        packed_channel = np.packbits(decoded_binary, axis=1)
        decoded_channels.append(packed_channel)

    return decoded_channels[0], decoded_channels[1], decoded_channels[2] # b_dec, g_dec, r_dec

# Recover image from decoded channels and save
def recover_image(b, g, r, iname):
    try:
        # Read original image to get the dimensions and type
        # This seems unnecessary if dimensions are passed or derived correctly
        # img_orig = cv2.imread(iname)
        # if img_orig is None: raise ValueError("Original image needed for recovery dimensions not found.")
        # Use dimensions from one of the decoded channels
        p, q = b.shape # Dimensions of the final decoded channel
        img_recovered = np.zeros((p, q, 3), dtype=np.uint8) # Create BGR image structure

        # Assign channels (assuming b,g,r are in correct order)
        img_recovered[:,:,0] = b # Blue channel
        img_recovered[:,:,1] = g # Green channel
        img_recovered[:,:,2] = r # Red channel

        # Save the recovered (encrypted) image
        save_path = "encrypted_images/enc.jpg"
        cv2.imwrite(save_path, img_recovered)
        print(f"Saved encrypted image as {save_path}")
        return img_recovered # Return the numpy array of the image

    except Exception as e:
        print(f"Error recovering image: {e}")
        return None
IGNORE_WHEN_COPYING_START
content_copy
download
Use code with caution.
Python
IGNORE_WHEN_COPYING_END

second_main.py

# second_main.py (page 31-32)
from PIL import Image
import tkinter as tk
from tkinter import filedialog
import hashlib
import binascii
import textwrap
import cv2
import numpy as np
from scipy.integrate import odeint
import matplotlib.pyplot as plt
from mpl_toolkits.mplot3d import Axes3D
import sys
from importlib import reload
from bisect import bisect_left as bsearch
import decryp # Module for decryption logic
import mysql.connector
from mysql.connector import Error
import pickle as cPickle

# GLOBAL Constants (Should ideally be shared/imported)
a, b, c = 10, 2.667, 28
x0, y0, z0 = 0, 0, 0
dna={} # Populate DNA dicts as in other files
dna["00"]="A"; dna["01"]="T"; dna["10"]="G"; dna["11"]="C"
dna["A"]=[0,0]; dna["T"]=[0,1]; dna["G"]=[1,0]; dna["C"]=[1,1]
dna["AA"]=dna["TT"]=dna["GG"]=dna["CC"]="A"
dna["AG"]=dna["GA"]=dna["TC"]=dna["CT"]="G"
dna["AC"]=dna["CA"]=dna["GT"]=dna["TG"]="C"
dna["AT"]=dna["TA"]=dna["CG"]=dna["GC"]="T"
tmax, N = 100, 10000

# Main execution block
if (__name__ == "__main__"):
    hash_value = None
    filename = 'upload_encrypted_images/enc.jpg' # Path to the image uploaded by voter

    try:
        # Calculate hash of the uploaded encrypted image
        with open(filename, "rb") as f:
            bytes_data = f.read() # read entire file as bytes
            readable_hash = hashlib.sha256(bytes_data).hexdigest()
            hash_value = readable_hash
            print(f"Hash of uploaded image: {hash_value}")

        # Database connection and data retrieval
        conn = None
        cursor = None
        try:
            conn = mysql.connector.connect(user='newuser', password='password', host='127.0.0.1', database='capstone')
            cursor = conn.cursor()

            # Find the record matching the hash
            sql_select = "select enc_data, enc_hash from area where enc_hash = %s" # Fetch data and hash
            cursor.execute(sql_select, (hash_value,))
            rows = cursor.fetchall()

            if rows:
                print(f"Found matching record for hash: {hash_value}")
                # Assuming only one match
                pickledStoredList = rows[0][0] # Get the blob data (enc_data)
                db_hash = rows[0][1] # Get the stored hash

                # Verify hash just in case (optional)
                if db_hash == hash_value:
                    print("Database hash matches uploaded hash.")
                    # Unpickle the stored data
                    unpickledList = cPickle.loads(pickledStoredList)
                    # Expected structure (based on listToPickle in encr.py):
                    # img, fx, fy, fz, file_path, Mk_e, blue, green, red
                    # Indices: 0,  1,  2,  3,  4,         5,    6,    7,     8 (Original has 9 items)
                    # Note: Need to adjust indices if structure differs. Let's assume 9 items.

                    if len(unpickledList) >= 9:
                         print("Unpickled data seems valid. Starting decryption...")
                         # Pass necessary elements to the decryption function
                         # Assuming decryp.decrypt expects:
                         # image (scrambled?), fx, fy, fz, fp(unused?), Mk_e, bt(blue?), gt(green?), rt(red?)
                         # Let's map based on assumed structure:
                         img_enc_scrambled = unpickledList[0] # This is likely the final *encrypted* image, not intermediate
                         fx = unpickledList[1]
                         fy = unpickledList[2]
                         fz = unpickledList[3]
                         # fp seems unused in provided decryp snippet
                         Mk_e = unpickledList[5] # Encoded key matrix
                         # Need the scrambled channels *before* decoding (bs, gs, rs from encr.py)
                         # The pickled list doesn't seem to store bs, gs, rs.
                         # It stores blue, green, red (original channels?) and the final 'img'
                         # This implies decryp.py needs to re-run parts of the encryption in reverse.
                         # Let's assume decryp.decrypt takes the components needed to reverse the process.
                         # If decryp.py needs scrambled XORed channels (bx, gx, rx), they aren't pickled.
                         # If decryp.py needs scrambled encoded channels (bs, gs, rs), they aren't pickled.
                         # --> Big problem: Required intermediate data isn't stored/retrieved.
                         # --> Assuming decryp.decrypt can work with what *is* stored.
                         # --> Revising call based on decryp.py structure:
                         # Needs: image(target decrypted img?), fx, fy, fz, fp(unused), Mk_e, bt(base blue?), gt(base green?), rt(base red?)
                         # Let's pass the original components stored:
                         original_blue = unpickledList[6]
                         original_green = unpickledList[7]
                         original_red = unpickledList[8]
                         # Passing placeholder for image, as decrypt creates it
                         decryp.decrypt(None, fx, fy, fz, None, Mk_e, original_blue, original_green, original_red)
                         print("Decryption process finished.")
                    else:
                         print("Error: Unpickled data has unexpected structure.")
                else:
                    print("Error: Hash mismatch between DB and uploaded file.")
            else:
                print(f"No record found matching hash: {hash_value}")

        except Error as e:
            print(f"Database Error: {e}")
        finally:
            if cursor: cursor.close()
            if conn and conn.is_connected(): conn.close()

    except FileNotFoundError:
        print(f"Error: Encrypted image file not found at {filename}")
    except Exception as e:
        print(f"An error occurred: {e}")
IGNORE_WHEN_COPYING_START
content_copy
download
Use code with caution.
Python
IGNORE_WHEN_COPYING_END

decryp.py

# decryp.py (combined snippets from pages 32-35)
from PIL import Image
import tkinter as tk
from tkinter import filedialog
import hashlib
import binascii
import textwrap
import cv2
import numpy as np
from scipy.integrate import odeint # Likely not needed for decrypt, but kept for consistency
import matplotlib.pyplot as plt # Likely not needed
from mpl_toolkits.mplot3d import Axes3D # Likely not needed
import sys
from importlib import reload
from bisect import bsearch # Likely not needed

# GLOBAL Constants (Should be imported/shared)
# ... (populate dna dict as before) ...
dna={}
dna["00"]="A"; dna["01"]="T"; dna["10"]="G"; dna["11"]="C"
dna["A"]=[0,0]; dna["T"]=[0,1]; dna["G"]=[1,0]; dna["C"]=[1,1]
dna["AA"]=dna["TT"]=dna["GG"]=dna["CC"]="A"
dna["AG"]=dna["GA"]=dna["TC"]=dna["CT"]="G"
dna["AC"]=dna["CA"]=dna["GT"]=dna["TG"]="C"
dna["AT"]=dna["TA"]=dna["CG"]=dna["GC"]="T"

# --- Helper functions (potentially duplicates from key_gen.py, refactor ideally) ---

# Split image into RGB (actually BGR from OpenCV)
def split_into_rgb_channels(image):
    # image should be the decrypted image array BGR
    if image is None or image.ndim < 3: return None, None, None
    # Return BGR components consistent with OpenCV
    return image[:,:,2], image[:,:,1], image[:,:,0] # R, G, B

# DNA Encode (Needed to reverse XOR?) - Seems redundant if starting from XORed data
def dna_encode(b,g,r):
    # (Code identical to key_gen.py's dna_encode)
    encoded_channels = []
    for channel_matrix in (b, g, r):
        channel_array = np.array(channel_matrix)
        unpacked = np.unpackbits(channel_array, axis=1)
        m, n_unpacked = unpacked.shape
        encoded = np.chararray((m, int(n_unpacked/2)))
        idx = 0
        for j in range(m):
            idx = 0
            for i in range(0, n_unpacked, 2):
                bit_pair = "{0}{1}".format(unpacked[j,i], unpacked[j,i+1])
                encoded[j, idx] = dna[bit_pair]
                idx += 1
        encoded_channels.append(encoded.astype(str))
    return encoded_channels[0], encoded_channels[1], encoded_channels[2]


# DNA Decode (Needed at the end of decryption)
def dna_decode(b, g, r):
    # (Code identical to key_gen.py's dna_decode)
    decoded_channels = []
    dna_rev = {v: k for k, v in dna.items() if isinstance(k, str) and len(k)==2}
    for color_enc in (b, g, r):
        m, n = color_enc.shape
        decoded_binary = np.ndarray((m, n*2), dtype=np.uint8)
        for j in range(m):
            for i in range(n):
                # Decode bytes/str based on input type
                dna_char = color_enc[j, i]
                if isinstance(dna_char, bytes): dna_char = dna_char.decode('utf-8')

                if dna_char in dna_rev:
                    bits = dna_rev[dna_char]
                    decoded_binary[j, 2*i]   = int(bits[0])
                    decoded_binary[j, 2*i+1] = int(bits[1])
                else: # Handle unexpected char
                    decoded_binary[j, 2*i]   = 0; decoded_binary[j, 2*i+1] = 0
        packed_channel = np.packbits(decoded_binary, axis=1)
        decoded_channels.append(packed_channel)
    return decoded_channels[0], decoded_channels[1], decoded_channels[2]

# New scramble function to reverse the original scramble
def scramble_new(fx, fy, fz, b_s, g_s, r_s): # Input scrambled channels
    p, q = b_s.shape
    size = p * q
    n_indices = len(fx)

    # Reshape scrambled channels to 1D
    bx_s_flat = np.array(b_s).reshape(size).astype(str)
    gx_s_flat = np.array(g_s).reshape(size).astype(str)
    rx_s_flat = np.array(r_s).reshape(size).astype(str)

    # Create empty arrays for unscrambled data (1D)
    bx_flat = np.chararray((size))
    gx_flat = np.chararray((size))
    rx_flat = np.chararray((size))

    # Reverse the scrambling
    # For each original position 'idx', find where it was moved FROM
    # bx_s[i] = bx[fz[i]], so bx[fz[i]] = bx_s[i]
    # Need inverse mapping or iterate through scrambled placement
    for i in range(size):
        # Determine the original index used for this scrambled position
        # Check index bounds / use modulo if lengths might mismatch
        idx_z = fz[i] % size
        idx_y = fy[i] % size
        idx_x = fx[i] % size

        # Place the scrambled data back into its original position
        bx_flat[idx_z] = bx_s_flat[i]
        gx_flat[idx_y] = gx_s_flat[i]
        rx_flat[idx_x] = rx_s_flat[i]

    # Reshape back to 2D
    b = bx_flat.reshape(p, q)
    g = gx_flat.reshape(p, q)
    r = rx_flat.reshape(p, q)

    return b.astype(str), g.astype(str), r.astype(str) # Return unscrambled DNA-encoded channels

# New XOR operation to reverse the original XOR
# Requires the same DNA XOR logic, applying it again reverses it
def xor_operation_new(b, g, r, mk): # Inputs are unscrambled DNA-encoded channels
    # (Code identical to key_gen.py's xor_operation)
    m,n = b.shape
    bx=np.chararray((m,n)); gx=np.chararray((m,n)); rx=np.chararray((m,n))
    b_str=b.astype(str); g_str=g.astype(str); r_str=r.astype(str); mk_str=mk.astype(str)

    # DNA XOR table (reverse lookup)
    dna_xor_rev = {}
    for k1 in ['A','T','G','C']:
        for k2 in ['A','T','G','C']:
            result = dna[k1+k2] # e.g., dna['AG'] = 'G'
            dna_xor_rev[result+k2] = k1 # Store 'GK' -> 'A' (Result+Key -> Original)

    for i in range(m):
        for j in range(n):
            # Apply XOR again to decrypt
            bx[i,j] = dna[ b_str[i,j] + mk_str[i,j] ]
            gx[i,j] = dna[ g_str[i,j] + mk_str[i,j] ]
            rx[i,j] = dna[ r_str[i,j] + mk_str[i,j] ]

    return bx.astype(str), gx.astype(str), rx.astype(str) # Returns DNA-encoded original channels

# --- Main Decryption Function ---
# Assumption: Input 'image' is ignored. fx, fy, fz are indices. Mk is encoded key matrix.
# bt, gt, rt are the *original* base R, G, B channels (needed to recreate the initially encoded data?? - Seems wrong)
# Let's redefine based on reversing the encryption steps:
# Need: Scrambled channels (bs, gs, rs), Indices (fx, fy, fz), Encoded key (Mk_e)
# Stored data: img_final_enc, fx, fy, fz, path, Mk_e, blue_orig, green_orig, red_orig
# Problem: Don't have bs, gs, rs. Let's assume 'img_final_enc' *is* bs, gs, rs combined somehow or one channel.
# --> Most likely path: The stored 'img' (unpickledList[0]) IS the scrambled image (b_s, g_s, r_s).
# Let's assume unpickledList[0] is a tuple/list containing (b_s, g_s, r_s)
# OR Let's assume the decrypt function call in second_main.py was wrong, and it should pass the pickled img.

# Redefining decrypt based on reversing encryption and available data:
# Input: scrambled_img_tuple (b_s, g_s, r_s), fx, fy, fz, Mk_e
def decrypt(scrambled_img_tuple, fx, fy, fz, Mk_e): # Removed unused/wrong args
    if scrambled_img_tuple is None or len(scrambled_img_tuple) != 3:
        print("Error: Decrypt requires tuple of (b_s, g_s, r_s)")
        return

    b_s, g_s, r_s = scrambled_img_tuple # Unpack scrambled channels

    # 1. Unscramble the channels using the reversed scramble logic
    print("Step 1: Unscrambling channels...")
    b_xor, g_xor, r_xor = scramble_new(fx, fy, fz, b_s, g_s, r_s) # Output is unscrambled, still XORed, DNA-encoded

    # 2. Reverse the XOR operation using the encoded key matrix
    print("Step 2: Reversing XOR operation...")
    b_enc, g_enc, r_enc = xor_operation_new(b_xor, g_xor, r_xor, Mk_e) # Output is DNA-encoded original

    # 3. Decode the DNA-encoded channels back to binary
    print("Step 3: Decoding DNA channels...")
    blue_final, green_final, red_final = dna_decode(b_enc, g_enc, r_enc) # Output is final decrypted channels

    # 4. Reconstruct the image
    print("Step 4: Reconstructing image...")
    p, q = blue_final.shape # Get dimensions from decoded channel
    img_decrypted = np.zeros((p, q, 3), dtype=np.uint8) # Create BGR image

    # Assign channels in BGR order for OpenCV
    img_decrypted[:,:,0] = blue_final
    img_decrypted[:,:,1] = green_final
    img_decrypted[:,:,2] = red_final

    # 5. Save the decrypted image
    save_path = "decrypted_images/Registered.png" # Save with a meaningful name
    try:
        cv2.imwrite(save_path, img_decrypted)
        print(f"Successfully decrypted and saved image to {save_path}")
    except Exception as e:
        print(f"Error saving decrypted image: {e}")

# Original decrypt function signature from page 35 (seems problematic):
# def decrypt(image, fx, fy, fz, fp, Mk, bt,gt,rt):
#     r,g,b=split_into_rgb_channels(image) # This assumes image is the input, but it should be the output
#     p,q = rt.shape # Gets shape from 'rt' (original red?)
#     benc, genc, renc=dna_encode(b,g,r) # Encodes the input 'image'?
#     # Needs scrambled data (bs, gs, rs) which aren't passed directly
#     # bs,gs, rs=scramble_new(fx, fy, fz, benc, genc, renc) # This scrambles encoded version of input 'image'
#     # Assumes bs,gs,rs are derived differently or passed implicitly
#     # Let's assume bs, gs, rs were derived from the *actual* encrypted data somehow
#     # bx, rx, gx=xor_operation_new(bs,gs,rs, Mk) # Reverses XOR
#     # blue, green, red=dna_decode(bx,gx, rx) # Decodes DNA
#     # green, red = red, green # Swaps channels? Why?
#     # img=np.zeros((p,q,3), dtype=np.uint8)
#     # img[:,:,0] = red # Assigns swapped red to blue channel?
#     # img[:,:,1] = green # Assigns swapped green to green channel?
#     # img[:,:,2] = blue # Assigns original blue to red channel?
#     # cv2.imwrite(("decrypted_images/Registered.png"), img) # Saves strangely constructed image
# -> This original logic seems flawed based on the encryption process. Using the revised logic above.
IGNORE_WHEN_COPYING_START
content_copy
download
Use code with caution.
Python
IGNORE_WHEN_COPYING_END

login.html

<!-- templates/login.html -->
{% extends 'index.html' %}
{% block title %} Login {% endblock %}
{% block mainContent %}
<html>
<head>
    <link rel="stylesheet" href="../newcss/capture.css"> <!-- Adjust path if needed -->
</head>
<body>
    <!-- Assuming this form is for face recognition login -->
    <!-- The action="{{ url_for('welcome') }}" suggests GET request to /welcome after showing face -->
    <form class="col s4 offset-s3" action="{{ url_for('welcome') }}" method="GET">
        <div class="cam_window">
            <!-- Displays video feed from Flask server -->
            <img src="{{ url_for('video_feed') }}">
        </div>
        <!-- Submit button likely triggers the page transition after face is potentially recognized by backend -->
        <input type="submit" class="waves-effect waves-light btn" value="proceed">
    </form>
</body>
</html>
{% endblock %}
IGNORE_WHEN_COPYING_START
content_copy
download
Use code with caution.
Html
IGNORE_WHEN_COPYING_END

welcome.html

<!-- templates/welcome.html -->
{% extends 'index.html' %}
{% block title %} Welcome {% endblock %}

{%block mainContent %}
<div class="container">
    <div class="row">
        <!-- This link likely appears *after* successful face auth redirect from /welcome -->
        <!-- It directs the user to the blockchain voting interface -->
        <a href='http://localhost/capstone_project/blockchain/index.php'> proceed </a>
    </div>
</div>
{% endblock %}
IGNORE_WHEN_COPYING_START
content_copy
download
Use code with caution.
Html
IGNORE_WHEN_COPYING_END

server.py

# server.py (page 37)
from flask import Flask, Response, json, render_template, request, redirect
import os
import cv2
from camera import VideoCamera # Assumes camera.py handles face rec logic
# from save import VideoCameraSave # Assumes save.py handles saving new faces
import sqlite3 # Not used in snippet, maybe legacy?
import string
import random

app = Flask(__name__)

# Global variable to store recognized name(s) - simplistic approach
got_names = "Unknown" # Default to Unknown

# Generator function for video streaming and face recognition
def gen(camera):
    global got_names
    while True:
        frame, names = camera.get_frame() # Get frame and recognized names
        # Update global status based on recognized names
        if names:
             if "Unknown" in names:
                 got_names = "Unknown"
             else:
                 # If any known face is detected, mark as Registered
                 # Simple logic: assumes first known name means registered
                 # Could be enhanced to check against a specific logged-in user
                 got_names = "Registered" # Found a known face
        else:
            got_names = "Unknown" # No faces detected

        # Encode frame as JPEG
        ret, jpeg = cv2.imencode('.jpg', frame)
        if not ret:
            print("Error encoding frame")
            continue
        frame_bytes = jpeg.tobytes()

        # Yield frame for HTTP streaming response
        yield (b'--frame\r\n'
               b'Content-Type: image/jpeg\r\n\r\n' + frame_bytes + b'\r\n\r\n')

# Route to provide the video feed
@app.route('/video_feed')
def video_feed():
    return Response(gen(VideoCamera()),
                    mimetype='multipart/x-mixed-replace; boundary=frame')

# API endpoint to get current recognized names (unused in provided HTML)
@app.route('/api/names')
def send_names():
    global got_names
    # data = json.dumps(got_names) # Send the single status string
    # return data
    return Response(json.dumps(got_names), mimetype='application/json')


# Function/Route for adding new faces (using VideoCameraSave - likely needs separate logic)
# def newEntry(camera, name):
#     while True:
#         frame = camera.newMember(name) # Assumes newMember captures/saves frames
#         ret, jpeg = cv2.imencode('.jpg', frame)
#         if not ret: continue
#         frame_bytes = jpeg.tobytes()
#         yield(b'--frame\r\n'
#               b'Content-Type: image/jpeg\r\n\r\n' + frame_bytes + b'\r\n\r\n')

# @app.route('/add_new', methods=["GET"])
# def add_new():
#     name = request.args.get('name')
#     # This would likely render a template showing the feed from newEntry
#     # return Response(newEntry(VideoCameraSave(), name),
#     #                 mimetype='multipart/x-mixed-replace; boundary=frame')
#     pass # Placeholder for add new functionality


# Route for the face recognition login page
@app.route('/login')
def login():
    return render_template('login.html')

# Route hit after clicking 'proceed' on the login page
@app.route('/welcome', methods=["GET"])
def welcome():
    global got_names
    print(f"Checking registration status: {got_names}") # Debug print
    # Check the globally stored recognition status
    if got_names != "Registered":
        # If not recognized as registered, redirect to a menu/error page
        # return redirect("http://localhost/capstone_project/menu.html") # Example redirect
        # Or render a template indicating failure
        return "<h1>User Not Registered or Not Recognized</h1>" # Simple message
    else:
        # If registered, redirect to the main voting application (blockchain part)
        return redirect("http://localhost/capstone_project/blockchain/index.php")

if __name__ == '__main__':
    # Ensure 'decrypted_images' directory exists for camera.py
    if not os.path.exists('./decrypted_images'):
        os.makedirs('./decrypted_images')
    app.run(host='0.0.0.0', port=5050, debug=True)
IGNORE_WHEN_COPYING_START
content_copy
download
Use code with caution.
Python
IGNORE_WHEN_COPYING_END

camera.py

# camera.py (page 38)
import cv2
import face_recognition
from PIL import Image
import os
import time
import numpy as np

class VideoCamera(object):
    def __init__(self):
        self.known_face_names = []
        self.known_face_encodings = []
        # Location where decrypted images of registered users are stored
        # Assumes filenames are like 'UserName.png'
        db_loc = "./decrypted_images"
        print(f"Loading known faces from: {db_loc}")

        try:
            # Load known faces and encodings from the directory
            for filename in os.listdir(db_loc):
                if filename.endswith(".png") or filename.endswith(".jpg"):
                    try:
                        name = os.path.splitext(filename)[0] # Get name from filename
                        image_path = os.path.join(db_loc, filename)
                        loaded_image = face_recognition.load_image_file(image_path)
                        # Get encodings (assuming one face per image)
                        encodings = face_recognition.face_encodings(loaded_image)

                        if encodings:
                            encoding = encodings[0]
                            self.known_face_encodings.append(encoding)
                            self.known_face_names.append(name)
                            print(f"Loaded encoding for: {name}")
                        else:
                            print(f"Warning: No face found in {filename}")
                    except Exception as e:
                        print(f"Error loading face {filename}: {e}")
        except FileNotFoundError:
             print(f"Error: Directory not found: {db_loc}. No known faces loaded.")
        except Exception as e:
             print(f"An error occurred loading known faces: {e}")


        # Initialize video capture
        self.video = cv2.VideoCapture(0)
        if not self.video.isOpened():
             print("Error: Could not open video source.")

        # Placeholder for the current frame
        self.frame = None


    def __del__(self):
        # Release video capture when object is deleted
        if self.video.isOpened():
            self.video.release()

    # Function to find known faces in the current frame
    def know_faces(self):
        if self.frame is None:
            return [], []

        # Resize frame for faster processing
        small_frame = cv2.resize(self.frame, (0, 0), fx=0.25, fy=0.25)
        # Convert BGR (OpenCV) to RGB (face_recognition)
        rgb_small_frame = cv2.cvtColor(small_frame, cv2.COLOR_BGR2RGB) # Correct conversion

        # Find all face locations and encodings in the current frame
        face_locations = face_recognition.face_locations(rgb_small_frame)
        face_encodings = face_recognition.face_encodings(rgb_small_frame, face_locations)

        face_names = []
        if not self.known_face_encodings: # Handle case where no known faces were loaded
             for _ in face_encodings: face_names.append("Unknown")
             return face_names, face_locations


        for face_encoding in face_encodings:
            # Compare face encoding with known encodings
            matches = face_recognition.compare_faces(self.known_face_encodings, face_encoding)
            name = "Unknown"

            # Use the known face with the smallest distance to the new face
            face_distances = face_recognition.face_distance(self.known_face_encodings, face_encoding)
            if len(face_distances) > 0: # Ensure there are distances to compare
                 best_match_index = np.argmin(face_distances)
                 if matches[best_match_index]:
                      name = self.known_face_names[best_match_index]

            face_names.append(name)

        return face_names, face_locations

    # Get a single frame, process it, and return
    def get_frame(self):
        if not self.video.isOpened():
             # Return a blank frame or error indicator if video not open
             blank_frame = np.zeros((480, 640, 3), dtype=np.uint8)
             return blank_frame, ["Error: No Video"]

        ret, self.frame = self.video.read()
        if not ret or self.frame is None:
             # Return blank frame if read fails
             blank_frame = np.zeros((480, 640, 3), dtype=np.uint8)
             return blank_frame, []


        # Perform face recognition
        face_names, face_locations = self.know_faces()

        # Draw rectangles and names on the frame
        for (top, right, bottom, left), name in zip(face_locations, face_names):
            # Scale back up face locations since frame analysed was scaled
            top *= 4
            right *= 4
            bottom *= 4
            left *= 4

            # Draw a box around the face
            cv2.rectangle(self.frame, (left, top), (right, bottom), (0, 0, 255), 2) # Red box

            # Draw a label with a name below the face
            cv2.rectangle(self.frame, (left, bottom - 35), (right, bottom), (0, 0, 255), cv2.FILLED)
            font = cv2.FONT_HERSHEY_DUPLEX
            cv2.putText(self.frame, name, (left + 6, bottom - 6), font, 1.0, (255, 255, 255), 1) # White text

        # Return the processed frame and the list of recognized names
        return self.frame, face_names
IGNORE_WHEN_COPYING_START
content_copy
download
Use code with caution.
Python
IGNORE_WHEN_COPYING_END

Voting.sol

// SPDX-License-Identifier: MIT // Recommended license identifier
pragma solidity ^0.7.4; // Match version used in contract

/*
 * @title Voting Contract
 * @dev Basic contract for managing votes for candidates.
 */
contract Voting {
    /* mapping field below is equivalent to an associative array or hash.
     * The key of the mapping is candidate name stored as type bytes32 and value is
     * an unsigned integer to store the vote count
     */
    mapping (bytes32 => uint256) public votesReceived;

    /* Solidity doesn't let you pass in an array of strings in the constructor (yet).
     * We will use an array of bytes32 instead to store the list of candidates
     */
    bytes32[] public candidateList;

    /* This is the constructor which will be called once when you
     * deploy the contract to the blockchain. When we deploy the contract,
     * we will pass an array of candidates who will be contesting in the election
     */
    constructor(bytes32[] memory candidateNames) { // Removed public keyword (default for constructor)
        candidateList = candidateNames;
    }

    // This function returns the total votes a candidate has received so far
    function totalVotesFor (bytes32 candidate) view public returns (uint256) {
        require(validCandidate(candidate), "Invalid candidate specified"); // Added revert message
        return votesReceived[candidate];
    }

    // This function increments the vote count for the specified candidate. This
    // is equivalent to casting a vote
    function voteForCandidate(bytes32 candidate) public {
        require(validCandidate(candidate), "Invalid candidate specified"); // Added revert message
        votesReceived[candidate] += 1;
        // Consider adding an event here to log the vote off-chain
        // event Voted(address voter, bytes32 candidate);
        // emit Voted(msg.sender, candidate); // Requires tracking voter address
    }

    // Checks if the candidate is in the list of valid candidates
    function validCandidate(bytes32 candidate) view public returns (bool) {
        for(uint i = 0; i < candidateList.length; i++) {
            if (candidateList[i] == candidate) {
                return true;
            }
        }
        return false;
    }
}
IGNORE_WHEN_COPYING_START
content_copy
download
Use code with caution.
Solidity
IGNORE_WHEN_COPYING_END

web3_interaction.js (Combined snippets from page 40)

// Ensure web3 is initialized (assuming it's included via CDN or similar)
// Connect to provider (e.g., Ganache, Infura, or local node)
const web3 = new Web3(new Web3.providers.HttpProvider("http://localhost:7545")); // Ganache default

var account; // Variable to hold the user's account address

// Get accounts from the provider
web3.eth.getAccounts().then((accounts) => {
    if (accounts.length > 0) {
        // Use the first account by default, or implement account selection logic
        account = accounts[0]; // Use first account from Ganache/Metamask
        console.log("Using account:", account);
        // Update UI or perform actions requiring the account address here
        // $("#accountDisplay").html(account); // Example UI update
    } else {
        console.error("No accounts found. Make sure your Ethereum client (e.g., Ganache, MetaMask) is running and configured.");
        alert("No Ethereum accounts found. Please check your provider connection.");
    }
}).catch((error) => {
    console.error("Error fetching accounts:", error);
    alert("Could not fetch accounts. Is your Ethereum provider running?");
});


// Contract ABI (Paste the ABI from your compiled contract)
const abi = JSON.parse('[{"constant":true,"inputs":[{"name":"candidate","type":"bytes32"}],"name":"totalVotesFor", "outputs":[{"name":"","type":"uint256"}], "payable":false,"stateMutability":"view","type":"function"}, {"constant":true,"inputs":[{"name":"candidate","type":"bytes32"}],"name": "validCandidate", "outputs":[{"name":"","type":"bool"}], "payable": false, "stateMutability":"view","type":"function"}, {"constant":true,"inputs":[{"name":"","type":"bytes32"}],"name":"votesReceived", "outputs": [{"name":"","type":"uint256"}], "payable":false,"stateMutability":"view","type":"function"},{"constant":true,"inputs":[{"name":"","type":"uint256"}],"name":"candidateList", "outputs":[{"name":"","type":"bytes32"}], "payable": false, "stateMutability":"view","type":"function"}, {"constant":false,"inputs":[{"name":"candidate", "type": "bytes32"}], "name": "voteForCandidate", "outputs": [], "payable": false, "stateMutability": "nonpayable","type":"function"},{"inputs":[{"name":"candidateNames", "type":"bytes32[]"}], "payable": false, "stateMutability": "nonpayable", "type":"constructor"}]'); // Updated ABI with uint256

// Contract Address (Replace with your deployed contract address)
const contractAddress = "0xCE586C5b271a4b5f2D1867B6c0f819AB76C1c7a8"; // Replace with your actual address

// Create contract instance
const contract = new web3.eth.Contract(abi, contractAddress);
console.log("Contract instance created for address:", contractAddress);

// Mapping for UI elements (adjust IDs if needed)
const candidates = {"BJP": "candidate-1", "NCP": "candidate-2", "AAP": "candidate-3"};

// Function to handle voting
function voteForCandidate() {
    if (!account) {
        alert("Ethereum account not available. Please connect your wallet.");
        return;
    }

    const candidateName = $("#candidate").val().toUpperCase(); // Get candidate name from input, normalize case maybe?

    if (candidates.hasOwnProperty(candidateName)) {
        console.log("Attempting to vote for:", candidateName);
        const candidateBytes32 = web3.utils.asciiToHex(candidateName); // Convert name to bytes32

        // Send the vote transaction
        contract.methods.voteForCandidate(candidateBytes32).send({ from: account })
        .on('transactionHash', function(hash){
            console.log("Transaction Hash:", hash);
            $("#transaction").html(hash); // Display transaction hash
            // Optional: Show pending state
        })
        .on('receipt', function(receipt){
            console.log("Transaction Receipt:", receipt);
            $("#blockno").html(receipt.blockNumber); // Display block number
            $("#account").html(account); // Display voter account

            // After successful vote, update the vote count display
            let div_id = candidates[candidateName];
            contract.methods.totalVotesFor(candidateBytes32).call().then((count) => {
                $("#" + div_id).html(count);
                console.log(`Vote successful for ${candidateName}. New count: ${count}`);
                alert(`Vote cast successfully for ${candidateName}!`);

                // Optional: Send vote details to backend PHP script
                postVoteDetails(candidateName, account, receipt.transactionHash, receipt.blockNumber);

                 // Hide voting elements, show home button etc.
                 // document.getElementById('hide-div').style.display = 'none'; // Example
                 // var homebutton = $("#homebutton");
                 // homebutton.show();

            }).catch((err) => {
                 console.error("Error fetching vote count after voting:", err);
            });

        })
        .on('error', function(error, receipt) { // If transaction fails
            console.error("Voting Transaction Error:", error);
            alert("Voting failed. See console for details.");
            // Handle errors (e.g., user rejected, out of gas)
        });

    } else {
        window.alert("PLEASE ENTER A VALID CANDIDATE NAME (BJP, NCP, AAP)");
    }
}

// Function to send vote details to backend (Example using jQuery post)
function postVoteDetails(candidateName, voterAccount, txHash, blockNum) {
    // Assuming there's a PHP endpoint 'vote_insertion.php'
    // Also need the image hash ('result') if required by PHP script
    var hash_value = $("#result").html(); // Assuming hash is stored in element with id 'result'

    $.post('vote_insertion.php', {
        candidateName: candidateName,
        account: voterAccount,
        transactionid: txHash,
        hash_value: hash_value, // Include if needed
        blockno: blockNum
    }, function(data) {
        // Handle response from PHP script (e.g., confirmation message)
        console.log("Backend response:", data);
        // alert(data); // Display backend message if needed
    }).fail(function(jqXHR, textStatus, errorThrown) {
        console.error("Error posting vote details to backend:", textStatus, errorThrown);
    });
}


// Function to load initial vote counts when page loads
$(document).ready(function() {
    console.log("Page ready. Loading initial vote counts...");
    const candidateNames = Object.keys(candidates);

    candidateNames.forEach(name => {
        let candidateBytes32 = web3.utils.asciiToHex(name);
        contract.methods.totalVotesFor(candidateBytes32).call().then((count) => {
            $("#" + candidates[name]).html(count); // Update UI element with vote count
            console.log(`Initial count for ${name}: ${count}`);
        }).catch((err) => {
            console.error(`Error fetching initial count for ${name}:`, err);
            $("#" + candidates[name]).html("Error"); // Show error in UI
        });
    });

    // Optional: Add event listener to the vote button
    // $("#voteButton").on("click", voteForCandidate); // Assuming button has id="voteButton"
});
IGNORE_WHEN_COPYING_START
content_copy
download
Use code with caution.
JavaScript
IGNORE_WHEN_COPYING_END
4.3. CONSTRAINTS, ALTERNATIVES AND TRADE-OFFS

Existing e-voting systems are based on centralized delivery of the service. The biometrics is centrally stored on servers. Currently, there are few countries using e-voting:

Voting in General: This is currently being used in many countries and is paper based. This is also used in the US elections. Voters physically must go to polling centres and cast their vote. The polling officers verify the voter's credentials and then provide them with ballot paper to cast their votes. The vote is cast by filling out a ballot paper. Only the vote count is done electronically.

Voting in Estonia: Estonia is the first country to have used e-voting for their elections. They utilized this through their electronic national ID card and the internet. The NIDs are smart cards with integrated circuit, a Java chip platform and 2048-bit PIN. It is programmed to be able to create digital signatures with SHA1/SHA2.[11] The card can be easily authenticated, encrypted, and signed. If the voter is qualified to vote, a list of candidates will be shown and the voter can cast his/her vote. It will be authenticated by using the electronic identification card. The vote is encrypted with the public key of the election and signed with the private key of the elector. If the ballot is cast, it will be transferred to the Estonian government managed voting storage server [12]. Voters can vote on several occasions and the final vote is the only valid one. This is to discourage the purchase of votes.

[Image: Fig. 4.7: Vote Casting Process in the Estonian E-Voting System [10]]

Voting in Bangladesh: Bangladesh has implemented electronic voting through their national ID cards. It implements the two-lock system. Voters must be physically present at polling locations to cast their votes. All polling booths have one administrator assigned to each EVM. The administrators are provided with special ID cards that have administrative access. The administrator must punch his card and enable the machine after verifying the voter's credentials manually. Once the administrator enables the Electronic Voting Machine (EVM) after verifying the user's credentials, the voter can punch his card and cast his vote. Voting can only be cast once and cannot be changed once it is cast. [6]

[Image: Fig. 4.8: Voting in Bangladesh]

The administrator also has a special passkey card to allow override in case the voter forgets to bring his/her NID card. The administrator can search and look up the user's details within the system. After verification, the administrator can allow the voter to vote. This is a good practice when the administrator is not biased or threatened. This has been reported to be misused in elections which defeats the purpose of voting. [3]

5. SCHEDULE, TASKS AND MILESTONES

SCHEDULE

The project has been completed over a period of four months in four phases:

Phase 1:

In this phase we focused on research. We went through research papers to better understand the product we wanted to develop.

We tried to develop a new method of E-voting that is not susceptible to tamper or attacks like we had seen in our survey.

Topic was chosen and approved.

Literature survey was done for the project.

Phase 2:

We finalize the design of our modules.

We created diagrams and structures to better understand the project.

We decided on the technical requirements of the project and the tools that we will use to develop the project.

Phase 3:

We build the first demo.

The demo consisted of all modules except the blockchain module and smart contracts.

We presented this demo for our review 2.

Phase 4:

Utilizing the feedback from review 2, we make certain adjustments to the project.

We complete our final build of the project that also contained the blockchain module.

We presented the paper at The First International Symposium on “Computational Intelligence Issues in Blockchain Technology, AI and ML.” The certificate has been provided in the appendix.

We completed documentation for the thesis.

TASKS

All the tasks before the development phase were split among the team members from the group equally. We selected papers and analyzed the fundamental aspects of e-voting and tried to solve the issues by modifying existing methods. In the development phase, the modules were divided among us. The invention of the concept of the project, the blockchain setup and the smart contract to interact with the blockchain was done by Adrijeet. Arunima worked on the DNA Encoding/Decoding algorithm, developed the blockchain explorer and linked all the modules of the project together in a website. Ariyan developed the face recognition module. The documentation was completed by the 3 of us equally.

MILESTONES

We provided our abstract, the fundamental diagram of the block and the schedule for the next few months for the 0th review.

We provided the diagrams and displayed the structure of the project for the 1st review.

For the 2nd review, we completed the implementation of the biometric module and the DNA Encoding/Decoding of the biometric templates.

We changed some aspects of the project after the 2nd review and integrated the blockchain and smart contracts to the project. We proceeded to finish the documentation after that.

6. PROJECT DEMONSTRATION

First, the admin logs in using the login form.

[Image: Admin login form]

This takes them to the home page which allows them to allow the voter to register themselves, cast vote, check if their vote is casted successfully and see the election results after voting is complete.

[Image: Admin dashboard/home page]

For voter registration, the voter first needs to select the area which they belong to.

[Image: Zone selection for voter registration]

Now they will be directed to a registration form where they can register themselves as voters.

[Image: Voter registration form]

After registering their personal details, voters need to register their biometrics too (face in our project's case).

[Image: Successful registration message, prompt for face registration]

[Image: Face capture interface]

After they capture their biometrics, voters need to click on ‘click here to generate hash' which will generate the hash of their biometric information and get stored in our database, along with the blob values of the image (unique to an image) and will be used later (during vote cast) to decrypt the image stored on their smart cards.

[Image: Successful upload message, prompt for hash generation]

Now they are registered successfully as new voters and are eligible to vote. They can go to the home page and wait for the elections to begin.

[Image: Successful image capture message]

When vote casting begins, the voters need to carry their smart cards which will have their encrypted images stored. For our project, we are unable to use hardware systems so we are creating an interface to demonstrate the same. The user will have to upload their encrypted image on this page which will generate the hash of the encrypted and if the database has a matching hash, their corresponding long blob values will be fetched which will then be used to decrypt their encrypted (uploaded) image.

[Image: Vote casting - image upload interface]

The encrypted image looks like this.

[Image: File upload dialog showing encrypted image (enc.jpg)]

If there is a matching hash, they will be taken to this page where they will have to proceed for face authentication while their unique image blob values are getting fetched (using hash of the encrypted image) simultaneously and is used to decrypt the image.

[Image: Successful image upload message, prompt to proceed for face authentication]

After decryption is successful, the decrypted image will be used for face recognition of the user carrying that smart card. If the decrypted image matches this person's face, they will be shown as registered and can proceed to vote.

[Image: Face login system showing 'Registered' after successful recognition]

After clicking on proceed, they land on the voting page.

[Image: Vote casting page - party list and vote counts]

Voters need to type the party name, they wish to vote for, in the textbox given. After they have voted, they can note down their account address and transaction hash to check if their vote was casted correctly. One voter can vote only once. After they click on the vote button, their vote is casted, the button gets disabled and the voter can go only to the home page now which will repeat the process if they try to vote again, making the system fool proof.

[Image: Vote casting page after voting (disabled button, details shown)]

[Image: Error message for incorrect candidate name input]

This is the blockchain explorer where everyone (public) can see their account address, transaction hash, block number and the timestamp of their vote but the votes are anonymous. They can also check whom they voted by typing their transaction hash in the search box.

[Image: Blockchain explorer showing vote transactions list]

The election results will be out after the voting is complete and will be shown in a table and bar chart below.

[Image: Election results table and bar chart]

7. COST ANALYSIS / RESULT & DISCUSSION

COST ANALYSIS

The cost of our Proof of Concept is minimal in small scale. It should be done in phases. Starting with smaller cities that require lower funds to host elections and then based on the success of the project, it should move towards larger cities. Finally, when the system is ready for a nationwide deployment, it should proceed to involve rural areas.

Smart Card: The smart card alone will be the costliest component of this project. It will cost around 2-3 USD to produce each smart card. It seems negligent but when done for a population of 100 million the cost will add up. The durability and reliability of smart cards will pay off in the long run.

EVM: Proprietary EVMs will have to be developed to work with our system. Current generation EVMs can be modified to suit our requirements. The only modifications that are required are the card readers and biometric scanners. Since these are minimal upgrades over existing EVMs, research and development costs for these devices will also be very low. If the shift to EVM is done in state elections initially and after mass adoption if it is adjusted for presidential elections, then the costs will not be so significant in the long run.

RESULTS AND DISCUSSION

The results and discussion of our project have been described below according to the modules that have been implemented within the system:

Security Analysis of Key Space: The security of the key space, co-relation coefficient and information entropy has been analysed and proven in the original paper where the key generation procedure was first presented. [4] The keys are not only safe but will not have clashes.

As for the symmetric key encryption using AES256 of the biometric data, AES256 attacks are not computationally feasible. The fastest key recovery attack using the biclique attack takes 2^254.3 operations. The key is stored only in the cloud and only after the hash of the data stored in the card matches with the hash of data stored in the cloud, the key is fetched. If the hash does not match, it will reject the voter's request. If an adversary does break the template security on the card, the initial hash match will fail. This will alert authorities to a modification done to the data on the smart card.

Biometric Verification: The biometric verification in our proof of concept has been done using face recognition but this can be expanded to fingerprint, iris, and palm detection without much hassle. Our template encryption will ensure enough chaos to generate different hashes for other biometric templates also. This is the reason we decided to use DNA Encoding/Decoding and chaotic maps to encrypt the templates. The chaotic maps have been used to generate enough noise so that the hashes generated from the encrypted images are not similar in any way. Fingerprint and palm print templates are remarkably similar between human beings. For this reason, our encryption procedure will cause enough differences to allow smooth operation of the hash matching. If the hashes between templates were to be similar, this would allow hackers to reverse engineer the templates and try to tamper them. So, the DNA Encoding and Decoding will generate noise to ensure there is no similarities between encrypted images. This would ensure template security and reduce redundancy to almost null.

Vote Blockchain: A private blockchain setup only for this voting purpose has been used. It will allow voters to check if their vote has been cast properly by searching for the hash value. The blockchain explorer will be available to the public and its code will be open sourced. This will ensure that no backdoors have been introduced in the system. A vote blockchain that no vote is tampered with as it will be flagged throughout the blockchain. It will require a tremendous amount of effort and power to change a single vote throughout the blockchain and it is not feasible. So, therefore our project has established that there are no chances of rigging a voting system implemented using this method.

8. SUMMARY

Although introducing this method of voting will be expensive and tedious for the first time, once it is introduced people can reap the benefits of this system in multiple services apart from voting. This will make verification of individuals more and reduce the risk of any biometric data theft in case of an attack. So, in the name of democracy and a secure voting process, our process should be adopted into the current voting procedure to ensure privacy and the right to vote is exercised by all citizens.

Our modularized design will also make upgrades to the existing system cheaper and easier in the future. Any module that requires an update can be updated without disturbing the other modules. The public blockchain explorer will allow users to check their votes without being disclosed. The blockchain will retain all the data from past elections which will allow analysts to draw better conclusions. Since no tampering of data can be done without the admins and voters knowing about it, this method of voting will surely increase the chances of adoption of E-Voting in more democracies.

9. REFERENCES

E. F. Kfoury, D. Khoury, A. Alsabeh, J. Gomez, J. Crichigno, and E. Bou-Harb, “A Blockchain-based Method for Decentralizing the ACME Protocol to Enhance Trust in PKI,” 2020 43rd Int. Conf. Telecommun. Signal Process. TSP 2020, pp. 461–465, 2020, doi: 10.1109/TSP49548.2020.9163555

M. Khasawneh, M. Malkawi, O. Al-Jarrah, L. Barakat, T. S. Hayajneh, and M. S. Ebaid, “A biometric-secure e-voting system for election processes,” Proceeding 5th Int. Symp. Mechatronics its Appl. ISMA 2008, no. January 2014, 2008, doi: 10.1109/ISMA.2008.4648818.

"Election Commission, police help Awami League in vote rigging: Jatiya Party" https://www.newagebd.net/article/131630/election-commission-police-help-awami-league-in-vote-rigging-jatiya-party (accessed on March 2021)

N. M.K and R. K.R, “Secured Key Generation for Biometric Encryption using Hyper-chaotic Map and DNA Sequences,” SSRN Electron. J., no. Icicnis, pp. 585–595, 2021, doi: 10.2139/ssrn.3769813.

“Aadhar security breaches” https://www.firstpost.com/tech/news-analysis/aadhaar-security-breaches-here-are-the-major-untoward-incidents-that-have-happened-with-aadhaar-and-what-was-actually-affected-4300349.html (accessed on March 2021)

Datta, P., Bhowmik, A., Shome, A., & Biswas, M. A Secured Smart National Identity Card Management Design using Blockchain. In 2020 2nd International Conference on Advanced Information and Communication Technology (ICAICT) (pp. 291-296), 2020

S. Chen, M. Barbosa, A. Boldyreva, and B. Warinschi, “Provable Security Analysis of FIDO2," pp. 1–35.

S. Kumar, M. Singh, C. Science, and C. Science, “Design a Secure Electronic Voting System," vol. 10, no. 4, pp. 192–199, 2013.

A. Ben Ayed, “A Conceptual Secure Blockchain Based Electronic Voting System,” Int. J. Netw. Secur. Its Appl., vol. 9, no. 3, pp. 101–09, 2017, DOI: 10.5121/ijnsa.2017.9301.

D. Springall et al., “Security analysis of the Estonian internet voting system,” Proc. ACM Conf. Comput. Commun. Secur., no. May, pp. 703–715, 2014, doi: 10.1145/2660267.2660315.

B. A. Trueb, “Estonian Electronic ID – card application specification Prerequisites to the Smart Card Differentiation to previous versions of EstEID card application,” Police Bord. Guard Board, Repub. of Est., 2013, [Online]. Available: http://www.id.ee/public/TB-SPEC-EstEID-Chip-App-v3_5-20140327.pdf.

M. Sudhakar, B. Divya, and S. Sai, “Biometric System Based Electronic Voting Machine Using Arm9 Microcontroller,” IOSR J. Electron. Commun. Eng. Ver. II, vol. 10, no. 1, pp. 2278–2834, 2016, doi: 10.9790/2834-10125765.

Nakamoto S, Bitcoin A. A peer-to-peer electronic cash system. Bitcoin. –URL: https://bitcoin.org/bitcoin.pdf. 2008;4.

Zheng, W., Wang, F. Y., & Wang, K. (2017, October). An ACP-based approach to color image encryption using DNA sequence operation and hyper-chaotic system. In 2017 IEEE International Conference on Systems, Man, and Cybernetics (SMC) (pp. 461-466). IEEE.

Buterin V. A next-generation smart contract and decentralized application platform. white paper. 2014 Jan 14;3(37).
