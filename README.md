AstraDose: Anticancer Drug Dosing Recommender System
=========================================

DESCRIPTION
-----------------------------------

Anticancer drug dose adjuster for patients with multiple organ
dysfunction syndrome.

Official Website - http://get-simple.info/
Github - https://github.com/GetSimpleCMS/GetSimpleCMS

GetSimple CMS was developed by Chris Cagle
It is now passionately supported and developed by a loving community.


LICENSE
-----------------------------------

This software package is licensed under the GNU GENERAL PUBLIC LICENSE v3.  
LICENSE.txt is located within this download's zip file

It would be great if you would link back to get-simple.info if you use it.


REQUIREMENTS
-----------------------------------

http://get-simple.info/docs/requirements

### Build Requirements ###

PHP 5.2+

### PHP Required Extensions ###

SimpleXML  
xml  
json  
dom  

curl (optional)  
gd (optional)  

### Browser Requirements ###

Javascript Enabled

### Server ###

*Apache ( required for out of the box security using .htaccess )

*If not using Apache you will get a non-apache warning, 
this warning is to alert you that your data files will not be secure 
and you must take proper precautions to secure your site.  
To disable this warning see gsconfig definition GSNOAPACHECHECK


INSTALLATION
-----------------------------------

Please see: http://get-simple.info/docs/installation


UPGRADING
-----------------------------------

Please see: http://get-simple.info/docs/upgrading


DISCLAIMER
-----------------------------------

While GetSimple strives to be a secure and stable application, we simply cannot 
be held liable for any information loss, corruption or anything else that may 
happen to your site while it is using the our software. 

If you find a bug or security hole, please contact someone in the forums at  
http://get-simple.info/forum


CREDITS
-----------------------------------

### TEAM ###

Founder / Creator: Chris Cagle  
Forum Handle: ccagle8  
Site: http://get-simple.info/forums/member.php?action=profile&uid=3  
Twitter: @ccagle8  
Location: Pittsburgh, Pennsylvania, USA  

Lead Developer: Shawn Alverson  
Forum Handle: shawn_a  
Site: http://get-simple.info/forums/member.php?action=profile&uid=1878  
Location: Tennessee, USA  


### THANKS ###

Mike Swan (n00dles)  
Carlos Navarro (cnb)  
Joshas  
Connie Connie Müller-Gödecke (Connie)  
Thorsten Panknin (polyfragmented)  
Mike Henken (MikeH)  
Martijn van der Ven (Zegnåt)  
...and the countless others on the forums and SVN that help us make this amazing product possible.  


Libraries
-----------------------------------

_company logos in the icons are copyright of their respective owners_

Vector Social Media Icons  
http://icondock.com/free/vector-social-media-icons  

Ckeditor  
http://ckeditor.com/

jcrop  
http://deepliquid.com/content/Jcrop.html

marijnh/CodeMirror  
http://codemirror.net/

fancybox  
https://github.com/fancyapps/fancyBox

rgrove/lazyload  
https://github.com/rgrove/lazyload

enyo/dropzone  
https://github.com/enyo/dropzone

fontawesome  
http://fontawesome.io/

bigspotteddog/scrolltofixed  
https://github.com/bigspotteddog/ScrollToFixed

dropzonejs  
http://www.dropzonejs.com/


APPENDIX
-----------------------------------

Adaptation of anticancer drugs in patients with renal
or hepatic impairment.

<table>
 <tbody>
   <tr>
     <td><strong>N</strong></td>
     <td><strong>Medicines</strong></td>
     <td><strong>Renal impairment</strong></td>
     <td><strong>Hepatic impairment</strong></td>
   </tr>
   <tr>
     <td>01</td>
     <td>ACETATE D&rsquo;ABIRATERONE</td>
     <td>No adaptation</td>
     <td>No adaptation</td>
   </tr>
   <tr>
     <td>02</td>
     <td>ACIDE ZOLEDRONIQUE</td>
     <td>CrCl &lt; 35 mL/min: CI</td>
     <td>No adaptation</td>
   </tr>
   <tr>
     <td>03</td>
     <td>AFATINIB</td>
     <td>No adaptation</td>
     <td>No adaptation</td>
   </tr>
   <tr>
     <td>04</td>
     <td>AFLIBERCEPT</td>
     <td>No adaptation</td>
     <td>No adaptation</td>
   </tr>
   <tr>
     <td>05</td>
     <td>ALEMTUZUMAB</td>
     <td>No adaptation</td>
     <td>No adaptation</td>
   </tr>
   <tr>
     <td>06</td>
     <td>AMASACRINE</td>
     <td>CrCl &lt; 30 mL/min: 70%</td>
     <td>
       <ul>
         <li>Bili &gt; 20mg/l: 60 -70%</li>
         <li>&gt; 36mg/l: 50 % or not recommended</li>
       </ul>
     </td>
   </tr>
   <tr>
     <td>07</td>
     <td>ASPARAGINASE</td>
     <td>No adaptation</td>
     <td>&gt; 36mg/l: CI</td>
   </tr>
   <tr>
     <td>08</td>
     <td>AXITINIB</td>
     <td>No adaptation</td>
     <td>No adaptation</td>
   </tr>
   <tr>
     <td>09</td>
     <td>AZACITIDINE</td>
     <td>Creatininemie &ge; 14-26 mg/L for men and 10-24 mg/L for women: 50%</td>
     <td>No adaptation</td>
   </tr>
   <tr>
     <td>10</td>
     <td>BENDAMUSTINE</td>
     <td>CrCl &lt; 40 mL/min: CI</td>
     <td>
       <ul>
         <li>Bili &lt; 12 mg/l: NA</li>
         <li>Bili 12mg/l &ndash; 30mg/l: 70%</li>
         <li>Bili &gt; 30mg/l : CI</li>
       </ul>
     </td>
   </tr>
   <tr>
    <td>11</td>
    <td>BEVACIZUMAB</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>12</td>
    <td>BLEOMYCINE</td>
    <td>
     <ul>
         <li>CrCl &lt; 50 mL/min: 70%</li>
         <li>CrCl &lt; 40 mL/min: 60%</li>
         <li>CrCl &lt; 30 mL/min: 55%</li>
         <li>CrCl &lt; 20 mL/min: 45%</li>
         <li>CrCl &lt; 10 mL/min: 40%</li>
     </ul>
    </td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>13</td>
    <td>BLINATUMOMAB</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>14</td>
    <td>BORTEZOMIB</td>
    <td>No adaptation</td>
    <td>
     <ul>
       <li>Bili &le;18mg/l: NA</li>
       <li>Bili &gt;18mg/l: 50%</li>
     </ul>
    </td>
   </tr>
   <tr>
    <td>15</td>
    <td>BRENTUXIMAB</td>
    <td>
     <ul>
       <li>CrCl &lt; 30 mL/min: 1,2 mg/k</li>
       <li>CrCl&nbsp; &lt; 15 mL/min: CI</li>
     </ul>
    </td>
    <td>
     <ul>
       <li>Bili: 12- 18mg/l: 66%</li>
       <li>Bili &gt;18- 36mg/L: CI</li>
     </ul>
    </td>
   </tr>
   <tr>
    <td>16</td>
    <td>CABAZITAXEL</td>
    <td>No adaptation</td>
    <td>
     <ul>
       <li>Bili&nbsp;: 12- 18mg/l&nbsp;or ASAT H&gt;40UI/L F &gt;38UI/L: 80%</li>
       <li>Bili 18- 36mg/L:60%</li>
       <li>&gt; 36mg/l: CI</li>
     </ul>
    </td>
   </tr>
   <tr>
    <td>17</td>
    <td>CAPECITABINE</td>
    <td>
     <ul>
       <li>CrCl &lt; 50 mL/min: 75 %</li>
       <li>CrCl &lt; 30 mL/min: CI</li>
     </ul>
    </td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>18</td>
    <td>CARBOPLATINE</td>
    <td>CALVERT</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>19</td>
    <td>CARFILOZOMIB</td>
    <td>CrCl &lt; 15 mL/min: 50%</td>
    <td>
     <ul>
       <li>Bili 12mg/l &ndash; 36mg/l: 75%</li>
       <li>&gt; 36mg/l: CI</li>
     </ul>
    </td>
   </tr>
   <tr>
    <td>20</td>
    <td>CETUXIMAB</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>21</td>
    <td>CHLORAMBUCIL</td>
    <td>
     <ul>
       <li>CrCl &lt; 60 mL/min: 1,5 to 9mg/day</li>
       <li>CrCl &lt; 15 mL/min: 1 to 6 mg/day</li>
     </ul>
    </td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>22</td>
    <td>CISPLATINE</td>
    <td>
     <ul>
       <li>CrCl &lt; 60 mL/min: 50 %</li>
       <li>CrCl &lt; 45 mL/min: 25 %</li>
       <li>CrCl &le; 30 mL/min: CI</li>
     </ul>
    </td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>23</td>
    <td>CLADRIBINE</td>
    <td>
     <ul>
       <li>CrCl &lt; 50 mL/min: 75%</li>
       <li>CrCl &lt; 10 mL/min: 50%</li>
     </ul>
    </td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>24</td>
    <td>CRISANTASPASE</td>
    <td>No adaptation</td>
    <td>BILI &gt;12mg/l: CI</td>
   </tr>
   <tr>
    <td>25</td>
    <td>CRIZOTINIB</td>
    <td>CrCl &le; 30 mL/min: 250 mg daily (no dialysis required), the dosage may be increased to 200 mg twice daily based on individual safety and tolerance.</td>
    <td>BILI &gt;12mg/l: CI</td>
   </tr>
   <tr>
    <td>26</td>
    <td>CYCLOPHOSPHAMIDE</td>
    <td>CrCl &lt; 10 mL/min: 50 %</td>
    <td>
     <ul>
       <li>T.Bil &gt; 31&ndash;50 mg/L or AST &gt; 180 IU/L: 75%</li>
       <li>T.Bil &gt; 50 mg/L: CI</li>
     </ul>
    </td>
   </tr>
   <tr>
    <td>27</td>
    <td>CYTARABINE</td>
    <td>
     <ul>
       <li>CrCl &lt; 60 mL/min: 50%</li>
       <li>CrCl &lt; 40 mL/min: 25 %</li>
     </ul>
    </td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>28</td>
    <td>DACARBAZINE</td>
    <td>
     <ul>
       <li>CrCl &lt; 60 mL/min: 75%</li>
       <li>CrCl &lt; 30 mL/min: 50%</li>
       <li>CrCl &lt; 10 mL/min: CI</li>
     </ul>
    </td>
    <td>T.Bil &gt; 36mg/l: CI</td>
   </tr>
   <tr>
    <td>29</td>
    <td>DACTINOMYCINE</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>30</td>
    <td>DASATINIB</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>31</td>
    <td>DAUNORUBICINE</td>
    <td>Creatininemie &gt; 30 mg/L: 50%</td>
    <td>
     <ul>
       <li>T.Bil 15&ndash;30 mg/L or AST 60&ndash;180 IU/L: 75%</li>
       <li>T.Bil &gt; 31&ndash;50 mg/L or AST &gt; 180 IU/L: 50%</li>
       <li>T.Bil &gt; 50 mg/L: CI</li>
     </ul>
    </td>
   </tr>
   <tr>
    <td>32</td>
    <td>DENOSUMAB</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>33</td>
    <td>DOXORUBICINE</td>
    <td>CrCl &lt; 10 mL/min: 75%</td>
    <td>
     <ul>
       <li>T.Bil 15&ndash;30 mg/L or AST 60&ndash;180 IU/L: 50%</li>
       <li>T.Bil &gt; 31&ndash;50 mg/L or AST &gt; 180 IU/L: 25%</li>
       <li>T.Bil &gt; 50 mg/L: CI</li>
     </ul>
    </td>
   </tr>
   <tr>
    <td>34</td>
    <td>DOCETAXEL</td>
    <td>No adaptation</td>
    <td>
     <ul>
       <li>ASAT H&gt;60UI/L F &gt;48UI/L or PAL H&gt;325 UI/L F &gt;262,5UI/L: 75%</li>
       <li>Bili &gt;12mg/l and/or [asat&nbsp; H&gt; 140 UI/L F &gt;112 UI/L with PAL H &gt;780UI/L&nbsp; F&gt; 630UI/L]: CI</li>
     </ul>
    </td>
   </tr>
   <tr>
    <td>35</td>
    <td>ENZALUTAMIDE</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>36</td>
    <td>EPIRUBICINE</td>
    <td>No adaptation</td>
    <td>
     <ul>
       <li>Bili 12-30mg/l or asat (H 80UI/L F 64UI/L &ndash; H160UI/L&nbsp; F128UI/L): 50%</li>
       <li>Bili &gt; 30mg/l or asat H160UI/L&nbsp; F128UI/L: 25%</li>
       <li>Bili&gt; 36mg/l: CI</li>
     </ul>
    </td>
   </tr>
   <tr>
    <td>37</td>
    <td>ERIBULINE</td>
    <td>CrCl&nbsp; &lt; 50 mL/min: 80%</td>
    <td>BILI &gt;36mg/l: CI</td>
   </tr>
   <tr>
    <td>38</td>
    <td>ERLOTINIB</td>
    <td>CrCl &lt; 10 mL/min: CI</td>
    <td>
     <ul>
       <li>AST H &ge; 120 UI/L&nbsp; F &ge;96UI/L or T.Bil 1&ndash;7 mg/L: &nbsp;50%</li>
       <li>T.Bil &gt; 70 mg/L: CI</li>
     </ul>
    </td>
   </tr>
   <tr>
    <td>39</td>
    <td>ETOPOSIDE</td>
    <td>
     <ul>
       <li>CrCl &lt; 50 mL/min: 75%</li>
       <li>CrCl &lt; 15 mL/min: CI</li>
     </ul>
    </td>
    <td>
     <ul>
       <li>T.Bil 15&ndash;30mg/L or AST 60&ndash;180 UI/L: 50%</li>
       <li>T.Bil &ge; 30 mg/L or AST &gt; 180 UI/L: CI</li>
     </ul>
    </td>
   </tr>
   <tr>
    <td>40</td>
    <td>EVEROLIMUS</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>41</td>
    <td>FLUDARABINE</td>
    <td>
     <ul>
       <li>CrCl &lt; 70 mL/min: 50%</li>
       <li>CrCl &lt; 30 mL/min: CI</li>
     </ul>
    </td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>42</td>
    <td>FLUOROURACILE</td>
    <td>No adaptation</td>
    <td>T.Bil &gt; 50 mg/L: CI</td>
   </tr>
   <tr>
    <td>43</td>
    <td>FULVESTRANT</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>44</td>
    <td>GEFITINIB</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>45</td>
    <td>GEMCITABINE</td>
    <td>No adaptation</td>
    <td>
     <ul>
       <li>Asat H &gt;40UI/L, F&gt;32UI/L: No adaptation</li>
       <li>T.Bil&gt;12mg/L: 80%</li>
     </ul>
    </td>
   </tr>
   <tr>
    <td>46</td>
    <td>HYDROXYCARBAMIDE</td>
    <td>
     <ul>
       <li>CrCl &lt;&nbsp; 60 mL/min: 75%</li>
       <li>CrCl &lt; 10 mL/min: 50%</li>
     </ul>
    </td>
    <td>
     <ul>
       <li>T.bili 15-50mg/L or Asat 60-180IU/L: 50%</li>
       <li>T.bili &gt;50mg/l or Asat &gt; 180 UI&nbsp;/l: CI</li>
     </ul>
    </td>
   </tr>
   <tr>
    <td>47</td>
    <td>IBRUTINIB</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>48</td>
    <td>IFOSFAMIDE</td>
    <td>
     <ul>
       <li>CrCl &lt; 60 mL/min: 80%</li>
       <li>CrCl &lt; 45 mL/min: 75%</li>
       <li>CrCl &lt; 30 mL/min: 70%</li>
       <li>CrCl &lt; 10 mL/min: CI</li>
     </ul>
    </td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>49</td>
    <td>IMATINIB</td>
    <td>CrCl &lt; 60 mL/min: 400 mg</td>
    <td>T.Bil &gt;12mg/l: 400 mg</td>
   </tr>
   <tr>
    <td>50</td>
    <td>IRINOTECAN</td>
    <td>No adaptation</td>
    <td>
     <ul>
       <li>Increased AST: No adaptation.</li>
       <li>T.Bil 18mg/l &ndash;36 mg/l&nbsp; and ratio of AST to ALT &lt; 5 &times; ULN: 75%</li>
       <li>T.Bil 37,2 mg/l &ndash;60mg/l and ratio of AST to ALT &lt; 5 &times; ULN: 40%</li>
       <li>T.Bil &lt; 18 mg/l ratio of AST to ALT 5.1&ndash;20 &times; ULN: 75%</li>
       <li>T.Bil 18mg/l &ndash;36 mg/l&nbsp; and ratio of AST to ALT 5.1&ndash;20 &times; ULN: 30%</li>
     </ul>
    </td>
   </tr>
   <tr>
    <td>51</td>
    <td>IDARUBICINE</td>
    <td>No adaptation</td>
    <td>Bili &gt;36mg/l: CI</td>
   </tr>
   <tr>
    <td>52</td>
    <td>LANREOTIDE</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>53</td>
    <td>LAPATINIB</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>54</td>
    <td>LENALIDOMIDE</td>
    <td>
     <ul>
       <li>CrCl &lt;&nbsp; 60 mL/min: 10 mg every 24h.</li>
       <li>CrCl &lt; 30 mL/min (does not require dialysis): 15 mg every 48h.</li>
       <li>CrCl &lt; 30 mL/min (requires dialysis): 5 mg/day.</li>
     </ul>
    </td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>55</td>
    <td>LENOGRASTIM</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>56</td>
    <td>MELPHALAN</td>
    <td>
     <ul>
       <li>CrCl &lt; 60 mL/min: 85%</li>
       <li>CrCl &lt; 45 mL/min: 75%</li>
       <li>CrCl &lt; 30 mL/min: 70%</li>
       <li>CrCl &lt; 10 mL/min: 50%</li>
     </ul>
    </td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>57</td>
    <td>MERCAPTOPURINE</td>
    <td>
     <ul>
       <li>CrCl &le; 50 mL/min: 50%</li>
       <li>CrCl &lt; 20 mL/min: CI</li>
     </ul>
    </td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>58</td>
    <td>METHOTRAXATE</td>
    <td>
     <ul>
       <li>CrCl&nbsp; &lt; 50 mL/min: 50%</li>
       <li>CrCl&nbsp; &lt; 15 mL/min: CI</li>
     </ul>
    </td>
    <td>
     <ul>
       <li>T.Bil 31&ndash;50 mg/L or AST &gt; 180 IU/L: 75%</li>
       <li>T.Bil &gt; 50mg/L: CI</li>
     </ul>
    </td>
   </tr>
   <tr>
    <td>59</td>
    <td>MITOMYCINE</td>
    <td>
     <ul>
       <li>CrCl &lt; 60 mL/min: 75%</li>
       <li>CrCl &lt; 30 mL/min: 50%</li>
       <li>CrCl &lt; 10 mL/min: CI</li>
     </ul>
    </td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>60</td>
    <td>NILOTINIB</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>61</td>
    <td>NIMOTUZUMAB</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>62</td>
    <td>NINTEDANIB</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>63</td>
    <td>NIVOLUMAB</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>64</td>
    <td>OXALIPLATINE</td>
    <td>CrCl &lt; 30 mL/min: CI</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>65</td>
    <td>PACLITAXEL</td>
    <td>No adaptation</td>
    <td>
     <ul>
       <li>Asat H&lt; 400UI/L&nbsp;F&lt; 320 UI/L and bili 19,2mg/l -24mg/l: 77%</li>
       <li>Asat H&lt; 400UI/L&nbsp;F&lt; 320 UI/L and bili 24,12mg/l -60mg/l: 51%</li>
       <li>Asat H&ge; 400UI/L&nbsp;F&ge; 320 UI/L and bili &gt; 60mg/l: not recommended&nbsp;&nbsp;or CI</li>
     </ul>
    </td>
   </tr>
   <tr>
    <td>66</td>
    <td>PALBOCICLIB</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>67</td>
    <td>PANITUMUMAB</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>68</td>
    <td>PAZOPANIB</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>69</td>
    <td>PEMBROLIZUM</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>70</td>
    <td>PEMETREXED</td>
    <td>CrCl &lt; 45 mL/min: CI</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>71</td>
    <td>PERTUZUMAB</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>72</td>
    <td>PRALATREXATE</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>73</td>
    <td>PROCARBAZINE</td>
    <td>CrCl &le; 30 mL/min: CI</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>74</td>
    <td>RAMUCIRUMAB</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>75</td>
    <td>REGORAFENIB</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>76</td>
    <td>RITUXIMAB</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>77</td>
    <td>ROMIPLOSTIME</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>78</td>
    <td>SORAFENIB</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>79</td>
    <td>SUNITINIB</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>80</td>
    <td>TARSTUZUMAB EMTANSINE</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>81</td>
    <td>TEMOZOLOMIDE</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>82</td>
    <td>THALIDOMIDE</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>83</td>
    <td>TRASTUZUMAB</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>84</td>
    <td>TRETINOINE</td>
    <td>reduit a 25 mg/m&sup2;/day</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>85</td>
    <td>TRI OXYDE D'ARSENIC</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>86</td>
    <td>VEMURAFENIB</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>87</td>
    <td>VINBLASTINE</td>
    <td>No adaptation</td>
    <td>
     <ul>
       <li>T.Bil 15&ndash;30 mg/dL or ASAT 60&ndash;180 IU/L: 50%</li>
       <li>T.Bil &gt; 31 mg/L or AST &gt; 180 IU/L: CI</li>
     </ul>
    </td>
   </tr>
   <tr>
    <td>88</td>
    <td>VINCRISTINE</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
   <tr>
    <td>89</td>
    <td>VINFLUNINE</td>
    <td>
     <ul>
       <li>CrCl&nbsp; &lt; 60 mL/min: 87,5%</li>
       <li>20 &lt; CrCl&nbsp; &lt; 40 mL/min: 75%</li>
     </ul>
    </td>
    <td>
     <ul>
       <li>Asat H&gt; 40UI/L F&gt; 32 UI/L and bili&gt;18mg/l: 78%</li>
       <li>Asat H&gt; 40UI/L F&gt;32 UI/L and bili&gt;36mg/l: 62%</li>
       <li>Asat H&ge; 100UI/L F&ge; 80 UI/L and bili &gt; 60mg/l: CI</li>
     </ul>
    </td>
   </tr>
   <tr>
    <td>90</td>
    <td>VINORELBINE</td>
    <td>No adaptation</td>
    <td>
     <ul>
       <li>T.Bil 25,2 mg/l &ndash;36mg/l: 50%</li>
       <li>T.Bil &gt; 36mg/l: 25%</li>
     </ul>
    </td>
   </tr>
   <tr>
    <td>91</td>
    <td>VISMODEGIB</td>
    <td>No adaptation</td>
    <td>No adaptation</td>
   </tr>
 </tbody>
</table>

______________________________________________
AstraDose: Anticancer Drug Dosing Recommender System - https://github.com/belazoui/AstraDose/
