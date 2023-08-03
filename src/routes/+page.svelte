<script>
    import Navbar from "$lib/Navbar.svelte";
    import Screen from "$lib/Screen.svelte";
    import SeedBox from "$lib/SeedBox.svelte";
</script>

<Navbar />
<Screen bg="bg01.png">
    <div class="w-full h-full flex items-center justify-center">
        <div
            class="p-2"
            style="background-color:rgba(255,255,255,0.6); max-width:400px;"
        >
            <p>Text here that describes the mission and vision of the dApp.</p>
            <br />
            <p>
                Explaining that our goal is to help people weather the
                volatility inherent to crypto, because nobody wants to be that
                person who sold BTC becuase it dropped all the way back down to
                $8.
            </p>
            <br />
            <p>
                The best time to plant a tree is either 20 years ago or RIGHT
                NOW. Money Trees allows users to safely store their crypto for
                the long haul, only to be available when the time is right.
            </p>
        </div>
    </div>
</Screen>
<Screen bg={"bg02.png"}>
    <div class="w-full h-full flex items-center justify-center">
        <div class="flex flex-wrap gap-4" style="max-width:600px;">
        <SeedBox>
            <div>Bonzai</div>
            <div>10 ERG</div>
            <div>10 Years</div>
        </SeedBox>
        <SeedBox>
            <div>Aspen</div>
            <div>100 ERG</div>
            <div>4 Years</div>
        </SeedBox>
        <SeedBox>
            <div>Oak</div>
            <div>1000 ERG</div>
            <div>4 Years</div>
        </SeedBox>
        <SeedBox>
            <div>Redwood</div>
            <div>1000 ERG</div>
            <div>10 Years</div>
        </SeedBox>
        <SeedBox>
            <div>Spruce</div>
            <div>10 ERG</div>
            <div>$50</div>
        </SeedBox>
        <SeedBox>
            <div>Cherry</div>
            <div>100 ERG</div>
            <div>$50</div>
        </SeedBox>
        <SeedBox>
            <div>Boabab</div>
            <div>1000 ERG</div>
            <div>$100</div>
        </SeedBox>
        <SeedBox>
            <div>Boabab</div>
            <div>1000 ERG</div>
            <div>$200</div>
        </SeedBox>
    </div></div>
</Screen>
<Screen bg={"bg03.png"}>
    <div class="w-full h-full flex items-center justify-center">
        <div
            class="p-2"
            style="background-color:rgba(255,255,255,0.6); max-width:400px;"
        >
            <p>
                Every forest begins with a single tree, grown from a single
                seed. Likewise, every fortune begins with a single investment.
                While this may seem simple, it is often difficult for people to
                have the patience required to allow their investments to grow.
                However, as every great investor knows, time is your greatest
                asset.
            </p>
        </div>
    </div>
</Screen>
<Screen bg={"bg04.png"}
    ><div class="w-full h-full gap-4 flex flex-col items-center justify-center">
        <div
            class="p-2"
            style="background-color:rgba(255,255,255,0.6); max-width:400px;"
        >
                “Time in the market beats timing the market”<br><br>
Sage advice. <br><br>
And the last remaining ingredient is persistence. <br><br>
Persistence beats genius, talent, and education every time. Invest with purpose, and do not stop. <br><br>
Plant as many seeds for your future as possible.  
        </div>
        <div            
        class="p-2 text-center"
        style="background-color:rgba(255,255,255,0.6); width:100%; max-width:400px;">
            <div class="font-bold text-xl">Leaderboard</div>
            <div class="flex decoration-dashed font-bold text-xl flex justify-between" style="border-style: dotted; border-top:2px dashed black; border-bottom:2px dashed black;">
                <div>Wallet</div>
                <div>Boxes</div>
                <div>ERG</div>
                <div>ERG-Years</div>
            </div>
            <div class="flex flex justify-between">
                <div>
                    <div>1. xxxx</div>
                    <div>2. xxxx</div>
                    <div>3. xxxx</div>
                    <div>4. xxxx</div>
                    <div>5. xxxx</div>
                    <div>6. xxxx</div>
                </div>
                <div>
                    <div>xxx</div>
                    <div>xxx</div>
                    <div>xxx</div>
                    <div>xxx</div>
                    <div>xxx</div>
                    <div>xxx</div>
                </div>
                <div>
                    <div>xxx</div>
                    <div>xxx</div>
                    <div>xxx</div>
                    <div>xxx</div>
                    <div>xxx</div>
                    <div>xxx</div>
                </div>
                <div>
                    <div>xxx</div>
                    <div>xxx</div>
                    <div>xxx</div>
                    <div>xxx</div>
                    <div>xxx</div>
                    <div>xxx</div>
                </div>
            </div>
        </div>
    </div>
</Screen>
<Screen bg={"bg05.png"}>div</Screen>
<Screen bg={"bg06.png"}>    <div class="w-full h-full flex items-center justify-center">
    <div
        class="p-2"
        style="background-color:rgba(255,255,255,0.6); "
    >
        <pre class="p-2">
// Contract with a delay of 500,000 blocks
&#123;
    val delay = 500000
    val backToSenderScript = proveDlog(senderPk)
    val heightIncreased = HEIGHT >= SELF.R4[Int].get + delay
    val backToSender = OUTPUTS.exists((box: Box) => box.propositionBytes == backToSenderScript.propBytes)
    heightIncreased && backToSender
&#125;
// Contract with a delay of 750,000 blocks
&#123;
    val delay = 750000
    val backToSenderScript = proveDlog(senderPk)
    val heightIncreased = HEIGHT >= SELF.R4[Int].get + delay
    val backToSender = OUTPUTS.exists((box: Box) => box.propositionBytes == backToSenderScript.propBytes)
    heightIncreased && backToSender
&#125;
// Contract with a delay of 1,000,000 blocks
&#123;
    val delay = 1000000
    val backToSenderScript = proveDlog(senderPk)
    val heightIncreased = HEIGHT >= SELF.R4[Int].get + delay
    val backToSender = OUTPUTS.exists((box: Box) => box.propositionBytes == backToSenderScript.propBytes)
    heightIncreased && backToSender
&#125;
        </pre>
    </div>
</div></Screen>
