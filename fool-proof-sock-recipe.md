------------------------------------------------------------
# FOOL PROOF TWO-AT-A-TIME TOE-UP SOCKS
------------------------------------------------------------

You need a 40 inc circular needle, and 8 yarn markers.

I use scrap yarn, from which I also make a counting yarn marker as a chain of knots.



## CAST ON

Use Judy's magic cast-on to cast 16 stitches per sock (8 sole stitches and 8 instep stitches, each for sock A and B)

Link to Judy's magic cast-on http://knitty.com/ISSUEspring06/FEATmagiccaston.html

* row 1, instep, sock A&B: knit all stitches
* row 1, sole,    sock B&A: knit all stitches through the backloop

Put yarn markers on the ends of the instep/sole row.

------------------------------------------------------------
# TOE INCREASE

First, pick your kind of increase from this link: http://www.knittinghelp.com/videos/increases
I prefer the lifted increase M1L (pull the bar with left needle from front onto left needle, knit through bar) and M1R (pull the bar with left needle from back onto left needle, pull loop loose, knit through bar). You can also do M1T and M1A on the previous row, but you may want to pull it real tight, or you get holes!

repeat the following two rows:

- row 2, instep sock A: K1 M1L K ...K M1R K
- row 2, instep sock B: K1 M1L K ...K M1R K
- row 2, sole    sock B: K1 M1L K ...K M1R K
- row 2, sole    sock A: K1 M1L K ...K M1R K

- row 3, instep & sole, A&B: Knit all stitches

For M1, you can use any increase you like, I recommend..
Link different increases.


Repeat row 2 and 3, until the sock fits loosely over your "ring toe"


------------------------------------------------------------
# FOOT

knit all stitches


------------------------------------------------------------
# GUSSET INCREASE

> Note, nowadays I skip this calculation and instead repeatedly try the sock on. Here is what to look for:
> 1. half way through the foot start increasing every other row. (see gusset increase)
> 2. when the sole reaches all the way to the back of the sole, start turning the heel (see make the heel)
> 3. stop decreasing heel stitches when the fit is good (see make the heel)



we work the gusset increase by repeating these two rows

- row i, instep sock A: K1 M1L K ...K M1R K
- row i, instep sock B: K1 M1L K ...K M1R K
- row i, sole    sock B: Knit all
- row i, sole    sock A: Knit all

- row i+1, instep & sole, A&B: Knit all stitches



but we first have to determine when to start the gusset increase:

- half way through the foot: 
   - Count the number of stitches you have on the needle as "count_foot" (instep + sole for one sock)
- Put on the sock and
   - Measure the circumference around the needle as `circ_foot`
   - Measure the maximal circumference around your heel as `circ_max`

Determine your stitch count per length unit `stitch_count` as
`stitch_count = count_foot / circ_foot`

At the widest point of the heel, you need `count_max` many stitches,
`count_max = stitch_count * circ_max`

In doubt, you rather want this number too high than too low


which means you have to increase by an additional number of $add_per_side$ stitches on both sides of each sock.
`add_per_side = (count_max - count_foot) / 2`

With the gusset increase pattern above, you will need to knit $num_gusset_rows$ many rows (counting the two repeated rows separately)
`num_gusset_rows = add_per_side *2`

You want to be done with the gusset increases when you hit the end of the foot.
Measure the length of $num_gusset_rows$ rows of your knitting so far as `gusset_length`

Start the gusset increase pattern when your knitting is `gusset_length` away from the heel.
Repeat the gusset increase patterns `num_gusset_rows / 2` times.



OPTIONAL strengthen farbric on last inch on the gusset:

Estimate the number of sole stitches that will be directly under your foot as `count_under`

On the sole, mark the middle `count_under` stitches with stitch markers

Change the gusset increase pattern to

- row i, instep sock A: K1 M1L K ...K M1R K
- row i, instep sock B: K1 M1L K ...K M1R K
- row i, sole    sock B: Knit until 1st marker, (K1 SL1)... until 2nd marker
- row i, sole    sock A: Knit until 1st marker, (K1 SL1)... until 2nd marker

- row i+1, instep & sole, A&B: Knit all stitches

- row i+2, instep sock A: K1 M1L K ...K M1R K
- row i+2, instep sock B: K1 M1L K ...K M1R K
- row i+2, sole    sock B: Knit until 1st marker, (SL1 K1)... until 2nd marker
- row i+2, sole    sock A: Knit until 1st marker, (SL1 K1)... until 2nd marker

- row i+3, instep & sole, A&B: Knit all stitches



------------------------------------------------------------
# MAKE THE HEEL (FLEEGLE HEEL)

I think this is the easiest and nicest looking heel.
Here is a video www.youtube.com/watch?v=qMrGhzUp6LE
Here is the blog article: http://fleeglesblog.blogspot.com/2007/09/no-sock-holes-for-you.html

Keep the previous markers, additionally mark the center stitch on both soles.

We knit the heel for each sock separately. First knit both insteps, now to work the first heel.

If you ended the gusset increase on row i+1 (instead of i+3) swap (K1 SL1) and (SL1 K1)  in the following.

- heel row 1, instep A&B: Knit all stitches
- heel row 1 sole sock B: Knit until first marker, (K1 SL1)... until 3 stitches after center stitch, SSK K1 turn
- heel row 2 sole sock B, wrong side: SL1  K1 K... until 3 stitches after the center stitch, P2tog P1 turn

remove center stitch marker on the next occasion, you still have two markers from the gusset increase on the sole of sock B


- heel row i, sole, sock B, right side: SL1,  knit while left of the 1st marker knit, between markers (SL1, K1), after 2nd marker Knit, until 1 stitch before the gap created by the turn, SSK, K1, turn

- heel row i+1, sole, sock B, wrong side: Knit until 1 stitch before the gap create by the turn, P2tog P1, turn

- heel row i+2, sole, sock B, right side: SL1,   outside the markers Knit, between markers (K1, SL1), until 1 stitch before the gap created by the turn, SSK, K1, turn

- heel row i+3, sole, sock B, wrong side: Knit until 1 stitch before the gap create by the turn, P2tog P1, turn


- repeat heel rows until you close the gap with the instep of sock B, ending on a right side row (i or i+2). The opposite end of the row will not be finished, that is okay.

Proceed to knit the heel of sock A, starting with heel row 1 sole sock A until you close the close the gap with instep of sock A, ending on a right side row.


Finish heel row:

- last heel row, instep, sock A & B: Knit
- last heel row, sole, sock B, if necessary, knit until 1 stitch before the gap, K2tog, Knit outside markers, (SL1, K1) [or respectively (K1 SL1)] between markers.

- last heel row, sole, sock A, if necessary, knit until 1 stitch before the gap, K2tog, Knit outside markers, (SL1, K1) [or respectively (K1 SL1)] between markers.


# RESCUE A HEEL THAT IS TOO TIGHT

I recommend to try on the the sock every few rows to check that it fits nicely but is not too tight. If it is too tight, you add increase stitches just on the outside of the two markers by changing "heel row i, sole, sock B, right side" to the following until the sock is wide enough.

- widen heel row i, sole, sock B, right side: SL1, knit until 1 stitch before 1st marker, M1L K1, then repeat (SL1 K1) until  2nd marker, then K1, M1R, then knit, until 1 stitch before the gap created by the turn, SSK, K1, turn

- widen heel row i+2, sole, sock B, wrong side: Knit until 1 stitch before the gap create by the turn, P2tog P1, turn





------------------------------------------------------------
# ANKLE PART OF LEG

- ankle row i, instep, sock A & B: Knit
- ankle row i, sole,  sock A & B: Knit outside markers,  (SL1, K1) [or respectively (K1 SL1)] between markers.

- ankle row i+1, instep & sole, sock A&B: Knit

- ankle row i+2, instep, sock A & B: Knit
- ankle row i, sole,  sock A & B: Knit outside markers,  (K1, SL1) [or respectively (SL1 K1)] between markers.

- ankle row i+3, instep & sole, sock A&B: Knit


you may replace the  SL1 K1 pattern with Knits any time.

you may decide to switch to the CUFF any time



------------------------------------------------------------
# CALF PART OF LEG

if you want to knit stockings, you will have to increase the sock to fit your calf. Try on the sock to notice when the stitches stretch out, now it is time for some more increases.

Depending on your pattern, you may either increase on either a) on both sides of the heel, b) on the inner side of the foot, or c) on the center stitch of the sole -not that it deserves that name anymore.

My calfs demand a single increase (b or c) on every other row, e.g. for variant b:

- calf row i, instep A&B: knit
- calf row i, sole, sock B: knit until one stitch remaining, M1 K1R
- calf row i, sole, sock B: K1 M1L, knit until end of row

- calf row i+1, instep & sole, A&B: knit


If you increase on both sides of the foot (variant a):

- calf row i, instep A&B: knit
- calf row i, sole, sock B: K1 M1L, knit until one stitch remaining, M1R K1
- calf row i, sole, sock B: K1 M1L, knit until one stitch remaining, M1R K1

- calf row i+1, instep & sole, A&B: knit
- calf row i+2, instep & sole, A&B: knit
- calf row i+3, instep & sole, A&B: knit




------------------------------------------------------------
# CUFF AND BIND OFF

The cuff is about 1 inch of K1P1 ribbing, make sure you have an even number of stitches for both socks.

cuff row i, instep & sole, sock A & B: K1P1

I prefer to add elastic thread to the garment to extra elasticity, which I purl together with the yarn but slip in the back when Knit


You may bind off - loosely! - however and whenever you like. If prefer to switch to double knitting and use the kitchener stitch to bind off, because this prevents the top from flaring.

# DOUBLE KNIT CUFF

* dk cuff row i: instep & sole, sock A&B: Knit knit stitches, slip the purl stitches (with yarn in back)
* dk cuff row i+1: instep & sole, sock A&B: Slip the knit stitches with yarn in front,  purl the purl stitches

This will also give a nice tube in which you can put an elastic bread, just before binding off.

# TUBULAR BIND OFF

Make sure the first stitch on the needle is a knit stitch (the second a purl)

Here a video, where knit stitches are red, and purl stitches are gray: http://www.youtube.com/watch?v=HqBGeKLlucA

cut the yarns, leaving a yarn tail of 4 times the length of the circumference of the last row.
thread the tail of first sock onto a darning needle


- pull the needle purlwise through the first knit stitch (leave stitch on needle)
- coming from the back, pull the needle knitwise though the first purl stitch (leave stitch on needle)  [I find it the easiest to first pull yarn from back between first knit and purl stitch to the front, then knitwise through the first purl stitch, and then back between the two stitches]


now repeat the following sequence

- pull needle knitwise through he first knit stitch, and push it off the needle
- pull needle purlwise through the next knit stitch (one after the purl), leaving it on the needle
- pull needle purlwise through the first purl stitch, and push it off the needle
- coming from behind, pull needle knitwise through the next purl stitch (second on the needle) [of pull between the first two stitches, then knitwise, back between the two stitches, leaving the stitches on the needle



repeat this sequence until there are only two stitches left on the needle, assuming it is 1 knit and a purl)

- pull needle knitwise through the first knit stitch, push it off the needle
- pull it purlwise through one of the already bound-off stitches to the left
- pull needle purlwise through the purl stitch (the last remaining stitch) sliding it off the needle
- pull the needle from front to back through an already bound-off stitch and weave in the tail.


You can also use a second needle as described in this blog: http://techknitting.blogspot.com/2008/01/tubular-cast-off-its-pretty.html


------------------------------------------------------------

# ADDING ELASTIC

Try on the sock. If it is too loose at some parts (e.g. around the ankle or the foot) or tends to slide down, I recommend to weave in elastic thread.

Pick a high quality elastic thread similar to the color of your yarn (well it only comes in black and white). Turn the sock inside out, so you weave it in on the wrong side.

Pick a row of purl bumps, thread elastic on darning needle. Pull elastic thread from left to right through one purl bump, and right to left through the next purl bump. Until you thread the row. Then move two rows to the side, and thread another round. Then pull elastic just as tight as need to be, knot the ends, weave in thread tails.


Don't forget to weave in yearn tails (e.g. from the toe)!
If you pull the knitting and it develops a hole (may happen around the heel decreases), darn it with the yarn.


