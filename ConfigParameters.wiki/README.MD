<table  >
    <tbody>
<tr>
        <td>Constant</td>
        <td>Description</td>
        <td>Default</td>
    </tr>
 <tr>
<td> kaptcha.border </td>
<td> Border around kaptcha. Legal values are yes or no. </td>
<td> yes </td>
</tr>

<tr>
<td> kaptcha.border.color </td>
<td> Color of the border. Legal values are r,g,b (and optional alpha) or white,black,blue. </td>
<td> black </td>
</tr>

<tr>
<td> kaptcha.border.thickness </td>
<td> Thickness of the border around kaptcha. Legal values are &gt; 0. </td>
<td> 1 </td>
</tr>

<tr>
<td> kaptcha.image.width </td>
<td> Width in pixels of the kaptcha image. </td>
<td> 200 </td>
</tr>

<tr>
<td> kaptcha.image.height </td>
<td> Height in pixels of the kaptcha image. </td>
<td> 50 </td>
</tr>

<tr>
<td> kaptcha.producer.impl </td>
<td> The image producer. </td>
<td> com.google.code.kaptcha.impl.DefaultKaptcha </td>
</tr>

<tr>
<td> kaptcha.textproducer.impl </td>
<td> The text producer. </td>
<td> com.google.code.kaptcha.text.impl.DefaultTextCreator </td>
</tr>

<tr>
<td> kaptcha.textproducer.char.string </td>
<td> The characters that will create the kaptcha. </td>
<td> abcde2345678gfynmnpwx </td>
</tr>

<tr>
<td> kaptcha.textproducer.char.length </td>
<td> The number of characters to display. </td>
<td> 5 </td>
</tr>

<tr>
<td> kaptcha.textproducer.font.names </td>
<td> A list of comma separated font names. </td>
<td> Arial, Courier </td>
</tr>

<tr>
<td> kaptcha.textproducer.font.size </td>
<td> The size of the font to use. </td>
<td> 40px. </td>
</tr>

<tr>
<td> kaptcha.textproducer.font.color </td>
<td> The color to use for the font. Legal values are r,g,b. </td>
<td> black </td>
</tr>

<tr>
<td> kaptcha.textproducer.char.space </td>
<td> The space between the characters </td>
<td> 2 </td>
</tr>

<tr>
<td> kaptcha.noise.impl </td>
<td> The noise producer. </td>
<td> com.google.code.kaptcha.impl.DefaultNoise </td>
</tr>

<tr>
<td> kaptcha.noise.color </td>
<td> The noise color. Legal values are r,g,b. </td>
<td> black </td>
</tr>

<tr>
<td> kaptcha.obscurificator.impl </td>
<td> The obscurificator implementation. </td>
<td> com.google.code.kaptcha.impl.WaterRipple </td>
</tr>

<tr>
<td> kaptcha.background.impl </td>
<td> The background implementation. </td>
<td> com.google.code.kaptcha.impl.DefaultBackground </td>
</tr>

<tr>
<td> kaptcha.background.clear.from </td>
<td> Starting background color. Legal values are r,g,b. </td>
<td> light grey </td>
</tr>

<tr>
<td> kaptcha.background.clear.to </td>
<td> Ending background color. Legal values are r,g,b. </td>
<td> white </td>
</tr>

<tr>
<td> kaptcha.word.impl </td>
<td> The word renderer implementation. </td>
<td> com.google.code.kaptcha.text.impl.DefaultWordRenderer </td>
</tr>

<tr>
<td> kaptcha.session.key </td>
<td> The value for the kaptcha is generated and is put into the HttpSession. This is the key value for that item in the session. </td>
<td> KAPTCHA_SESSION_KEY </td>
</tr>

<tr>
<td> kaptcha.session.date </td>
<td> The date the kaptcha is generated is put into the HttpSession. This is the key value for that item in the session. </td>
<td> KAPTCHA_SESSION_DATE </td>
</tr>
</tbody>
</table>
