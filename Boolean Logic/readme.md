# बुलियन तर्क

बूलियन तर्कशास्त्र गणित की एक शाखा है जो सत्य और असत्य के मूल्यों से संबंधित है। यह तर्क की एक प्रणाली है जो क्रमशः असत्य और सत्य का प्रतिनिधित्व करने के लिए केवल दो मानों, 0 और 1 का उपयोग करती है। इसे बूलियन बीजगणित के रूप में भी जाना जाता है, जिसका नाम जॉर्ज बूले के नाम पर रखा गया है, जिन्होंने पहली बार 1854 में इसका वर्णन किया था।

निर्णय लेने में सहायता के लिए प्रोग्राम सरल तुलनाओं का उपयोग करते हैं। बूलियन तर्क बीजगणित का एक रूप है जहां सभी मान या तो सत्य या गलत होते हैं। सत्य और असत्य के इन मूल्यों का उपयोग उन स्थितियों का परीक्षण करने के लिए किया जाता है जिनके आधार पर चयन और पुनरावृत्ति आधारित होती है।

## सामान्य बूलियन ऑपरेटर्स

| ऑपरेटर | नाम |               विवरण               |
| :------: | :--: | :-------------------------------------: |
|    !     | नहीं  |    ऑपरेंड के मूल्य को नकारता है।    |
|    &&    | तथा  | यदि दोनों ऑपरेंड सत्य हैं तो सत्य लौटाता है। |
|   \|\|   |  या  | यदि कोई भी ऑपरेंड सत्य है तो सत्य लौटाता है। |

## बूलियन बीजगणित

बूलियन बीजगणित बीजगणित की एक शाखा है जिसमें चर के मान सत्य मान सत्य और असत्य होते हैं, जिन्हें आमतौर पर क्रमशः 1 और 0 दर्शाया जाता है। प्रारंभिक बीजगणित के बजाय जहां चर के मान संख्याएं हैं और मुख्य संक्रियाएं जोड़ और गुणा हैं, बूलियन बीजगणित की मुख्य संक्रियाएं संयोजन (निरूपित ∧), विच्छेदन (निरूपित ∨), और निषेध (निरूपित ¬) हैं। इन ऑपरेशनों को क्रमशः तार्किक AND, तार्किक OR और तार्किक NOT के रूप में भी जाना जाता है।

### बीजगणितीय नियम

बूलियन बीजगणित के निम्नलिखित नियम हैं:

- क्रमविनिमेय नियम: a ∧ b = b ∧ a और a ∨ b = b ∨ a
- सहयोगी कानून: (ए ∧ बी) ∧ सी = ए ∧ (बी ∧ सी) और (ए ∨ बी) ∨ सी = ए ∨ (बी ∨ सी)
- वितरणात्मक कानून: a ∧ (b ∨ c) = (a ∧ b) ∨ (a ∧ c) और a ∨ (b ∧ c) = (a ∨ b) ∧ (a ∨ c)
- पहचान कानून: a ∧ 1 = a और a ∨ 0 = a
- प्रभुत्व नियम: a ∧ 0 = 0 और a ∨ 1 = 1
- दोहरा निषेध नियम: ¬¬a = a
- निष्प्रभावी कानून: a ∧ a = a और a ∨ a = a
- अवशोषण नियम: a ∨ (a ∧ b) = a और a ∧ (a ∨ b) = a

### डी मॉर्गन के नियम
प्रस्तावात्मक तर्क और बूलियन बीजगणित में, डी मॉर्गन के नियम परिवर्तन नियमों की एक जोड़ी हैं जो अनुमान के दोनों वैध नियम हैं। नियम संयोजन और विच्छेद की अभिव्यक्ति को विशुद्ध रूप से निषेध के माध्यम से एक दूसरे के संदर्भ में करने की अनुमति देते हैं।

नियमों को अंग्रेजी में इस प्रकार व्यक्त किया जा सकता है:
- नहीं (a या b) = (नहीं a) और (नहीं b)
- नहीं (a और b) = (नहीं a) or (नहीं b)

सेट सिद्धांत और बूलियन बीजगणित में, इन्हें औपचारिक रूप से इस प्रकार लिखा जाता है:
- ¬(a ∨ b) = (¬a) ∧ (¬b)
- ¬(a ∧ b) = (¬a) ∨ (¬b)

नोट: यहां '^' का उपयोग तार्किक AND ऑपरेशन को दर्शाने के लिए किया जाता है और 'v' का उपयोग तार्किक OR ऑपरेशन को दर्शाने के लिए किया जाता है।

## बूलियन ऑपरेटर्स

बूलियन कमांड का एक सेट है जिसका उपयोग लगभग हर खोज इंजन, डेटाबेस या ऑनलाइन कैटलॉग में किया जा सकता है। सबसे लोकप्रिय बूलियन कमांड हैं AND, OR, और NOT। बूलियन ऑपरेटरों का उपयोग अधिक जटिल अभिव्यक्ति बनाने के लिए दो या दो से अधिक अभिव्यक्तियों को संयोजित करने के लिए किया जाता है। बूलियन ऑपरेटर का परिणाम हमेशा बूलियन मान होता है, या तो सही या गलत। निम्न तालिका जावास्क्रिप्ट में बूलियन ऑपरेटरों को सूचीबद्ध करती है।

| ऑपरेटर | विवरण |
| -------- | ----------- |
| && | तार्किक और |
| \|\| | तार्किक या |
| ! | तार्किक नहीं |

### Truth Table

Truth tables are used to represent the logical relationships between Boolean variables. A truth table is a table that shows the logical relationships between the input variables and the output variables. The input variables are the variables that are used to calculate the output variables. The output variables are the variables that are calculated from the input variables.

### AND Truth Table

The AND truth table is shown below.
| A | B | A && B |
|---|---|--------|
| 0 | 0 | 0 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |

### OR Truth Table

The OR truth table is shown below.
| A | B | A \|\| B |
|---|---|----------|
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 1 |

### NOT Truth Table

The NOT truth table is shown below.
| A | !A |
|---|----|
| 0 | 1 |
| 1 | 0 |

### Boolean Expressions

A boolean expression is combination of boolean operators,constants and variables combined together to evalute to boolean value.Basically they help in mathematically representing the various boolean circuits thereby allowing the designer to analyse them easily.
Example: f(A,B)=AB'+A'B

### Canonical and Standard forms of Boolean Expressions

Suppose there are two input variables (x,y) in the system .
We can get four Boolean product terms by combining two variables x and y with logical AND operation. These Boolean product terms are called as **min terms** or **standard product terms**. The min terms are x’y’, x’y, xy’ and xy.

A min term always evaluates to one.

So suppose x=0 and y=1 .So the corresponding minterm will be x'y.

Similarly, we can get four Boolean sum terms by combining two variables x and y with logical OR operation. These Boolean sum terms are called as **max terms** or **standard sum terms**. The Max terms are x + y, x + y’, x’ + y and x’ + y’.

A max term always evaluates to zero .

So suppose x=0 and y=1 .So the corresponding minterm will be x+y'.

#### Representation of possibilities:

| x   | y   | Min Term | Max Term |
| --- | --- | -------- | -------- |
| 0   | 0   | x'y'     | x+y      |
| 0   | 1   | x'y      | x+y'     |
| 1   | 0   | xy'      | x'+y     |
| 1   | 1   | xy       | x'+y'    |

### Canonical Expressions

There are either sum of product(SOP) of minterms or product of sums(POS) of all maxterms in the boolean system which help in giving the boolean result of the system.

**Example:** Suppose a two variable system(x,y) has the following output combination.

| x   | y   | Output | Minterms | Maxterms |
| --- | --- | ------ | -------- | -------- |
| 0   | 0   | 0      | ---      | x+y      |
| 0   | 1   | 1      | x'y      | ---      |
| 1   | 0   | 1      | xy'      | ---      |
| 1   | 1   | 0      | ---      | x'+y'    |

Canonical SOP expression:- x'y+xy'.

Canonical SOP expression:- (x+y)(x'+y').

### Basic Operations

The basic operations of Boolean algebra are conjunction, disjunction, and negation. These Boolean operations are expressed with the corresponding binary operators AND, and OR and the unary operator NOT, collectively referred to as Boolean operators.

The basic Boolean operations on variables x and y are defined as follows:

| Logical operation | Operator | Notation | Alternative notations | Definition                              |
| ----------------- | -------- | -------- | --------------------- | --------------------------------------- |
| Conjunction       | AND      | x∧y      | x AND y, Kxy          | x∧y = 1 if x = y = 1, x∧y = 0 otherwise |
| Disjunction       | OR       | x∨y      | x OR y, Axy           | x∨y = 0 if x = y = 0, x∨y = 1 otherwise |
| Negation          | NOT      | ¬x       | NOT x, Nx, x̅, x', !x  | ¬x = 0 if x = 1, ¬x = 1 if x = 0        |

Alternatively the values of x∧y, x∨y, and ¬x can be expressed by tabulating their values with truth tables as follows:

![basic-operation-boolean-logic](https://user-images.githubusercontent.com/62456215/193660730-f9df2314-95d2-49d9-9831-41ce41c7180b.jpg)

If the truth values 0 and 1 are interpreted as integers, these operations may be expressed with the ordinary operations of arithmetic (where x + y uses addition and xy uses multiplication), or by the minimum/maximum functions:

![basic-operation-boolean-logic-2](https://user-images.githubusercontent.com/62456215/193661769-dd7b2551-7f18-4b7a-bd4c-bce4045f9956.jpg)

One might consider that only negation and one of the two other operations are basic, because of the following identities that allow one to define conjunction in terms of negation and the disjunction, and vice versa ([De Morgan's laws](https://en.wikipedia.org/wiki/De_Morgan%27s_laws)):

![basic-operation-boolean-logic-3](https://user-images.githubusercontent.com/62456215/193661772-a25dd7c9-d1f2-4a08-8b33-7e1c87dd6488.jpg)

### K-Map method of Boolean Reduction

The major problem with large boolean expression is that it is very difficult to reduce them with boolean logical operators.Hence K-Map is a graphical method of reduction which eases the task upto 5 input variables.

#### 2 variable K-Map

The number of cells in 2 variable K-map is four, since the number of variables is two. The following figure shows 2 variable K-Map.

2 Variable K-Map

![image](https://user-images.githubusercontent.com/65187507/193468957-4eb297af-2d32-4ba8-bef3-904624e984ca.png)

![image](https://user-images.githubusercontent.com/65187507/193468966-30c01e97-e48b-4c16-90c2-f983cdeab5ef.png)

- There is only one possibility of grouping 4 adjacent min terms.

- The possible combinations of grouping 2 adjacent min terms are {(m0, m1), (m2, m3), (m0, m2) and (m1, m3)}.

#### 3 Variable K-Map

The number of cells in 3 variable K-map is eight, since the number of variables is three. The following figure shows 3 variable K-Map.

3 Variable K-Map

![image](https://user-images.githubusercontent.com/65187507/193469022-296494d5-9fa7-4406-b51d-58c1276fa864.png)

There is only one possibility of grouping 8 adjacent min terms.

- The possible combinations of grouping 4 adjacent min terms are {(m0, m1, m3, m2), (m4, m5, m7, m6), (m0, m1, m4, m5), (m1, m3, m5, m7), (m3, m2, m7, m6) and (m2, m0, m6, m4)}.

- The possible combinations of grouping 2 adjacent min terms are {(m0, m1), (m1, m3), (m3, m2), (m2, m0), (m4, m5), (m5, m7), (m7, m6), (m6, m4), (m0, m4), (m1, m5), (m3, m7) and (m2, m6)}.

- If x=0, then 3 variable K-map becomes 2 variable K-map.

#### 4 Variable K-Map

The number of cells in 4 variable K-map is sixteen, since the number of variables is four. The following figure shows 4 variable K-Map.

![image](https://user-images.githubusercontent.com/65187507/193469057-82edb678-22b8-4eac-b3a5-4693de5075cd.png)

- There is only one possibility of grouping 16 adjacent min terms.

- Let R1, R2, R3 and R4 represents the min terms of first row, second row, third row and fourth row respectively. Similarly, C1, C2, C3 and C4 represents the min terms of first column, second column, third column and fourth column respectively. The possible combinations of grouping 8 adjacent min terms are {(R1, R2), (R2, R3), (R3, R4), (R4, R1), (C1, C2), (C2, C3), (C3, C4), (C4, C1)}.

- If w=0, then 4 variable K-map becomes 3 variable K-map.

#### 5 Variable K-Map

The number of cells in 5 variable K-map is thirty-two, since the number of variables is 5. The following figure shows 5 variable K-Map.

5 Variable K-Map

![image](https://user-images.githubusercontent.com/65187507/193469399-f8cb0101-1b9a-4d35-8ee7-3d9236ddb521.png)

- There is only one possibility of grouping 32 adjacent min terms.

- There are two possibilities of grouping 16 adjacent min terms. i.e., grouping of min terms from m0 to m15 and m16 to m31.

- If v=0, then 5 variable K-map becomes 4 variable K-map.

- In the above all K-maps, we used exclusively the min terms notation. Similarly, you can use exclusively the Max terms notation.

### Minimization of Boolean Functions using K-Maps

If we consider the combination of inputs for which the Boolean function is ‘1’, then we will get the Boolean function, which is in standard sum of products form after simplifying the K-map.

Similarly, if we consider the combination of inputs for which the Boolean function is ‘0’, then we will get the Boolean function, which is in standard product of sums form after simplifying the K-map.

Follow these rules for simplifying K-maps in order to get standard sum of products form.

- Select the respective K-map based on the number of variables present in the Boolean function.

- If the Boolean function is given as sum of min terms form, then place the ones at respective min term cells in the K-map. If the Boolean function is given as sum of products form, then place the ones in all possible cells of K-map for which the given product terms are valid.

- Check for the possibilities of grouping maximum number of adjacent ones. It should be powers of two. Start from highest power of two and upto least power of two. Highest power is equal to the number of variables considered in K-map and least power is zero.

- Each grouping will give either a literal or one product term. It is known as prime implicant. The prime implicant is said to be essential prime implicant, if atleast single ‘1’ is not covered with any other groupings but only that grouping covers.

- Note down all the prime implicants and essential prime implicants. The simplified Boolean function contains all essential prime implicants and only the required prime implicants.

- Note 1 − If outputs are not defined for some combination of inputs, then those output values will be represented with don’t care symbol ‘x’. That means, we can consider them as either ‘0’ or ‘1’.

- Note 2 − If don’t care terms also present, then place don’t cares ‘x’ in the respective cells of K-map. Consider only the don’t cares ‘x’ that are helpful for grouping maximum number of adjacent ones. In those cases, treat the don’t care value as ‘1’.
