<template>
    <section>
    
        <div class="bg-parallax-photo">
            <parallax :speed-factor="0.5" sectionClass="parallax-outside" containerClass="parallax-inside">
                <img src="@/assets/bg-triangle-pink2.png" class="float-right float-md-none" />
            </parallax>
        </div>
        
        <div class="container py-5">
            <div class="row justify-content-md-end">
                <div class="col-md-5 py-md-5">
                    <h1 class="text-blue my-md-5">Answering the call by building a community.</h1>
                    <p>It started with the Digital Services Playbook, which outlines 13 key “plays” to help the government build more successful digital services. Robert Rasmussen, the CEO of Agile Six, saw this as an opportunity to improve how government contractors could deliver these services by nurturing a sense of community, rather than rivalry.</p>
                    <p>He approached other like-minded companies to create the Digital Services Coalition as a place to share knowledge, find teaming partners for government proposals, and mentor firms who want to get involved in rethinking how the government delivers digital services. By creating this community, we can all bring our best talents to the table and learn from each other’s successes and failures.</p>
                </div>
            </div>
        </div>

        <div class="bg-parallax">
            <parallax :speed-factor="0.3" sectionClass="parallax-outside" containerClass="parallax-inside">
                <img src="@/assets/bg-triangle-gray.png" />
            </parallax>
        </div>
        
        <div class="container py-5">
            <div class="row">
                <div class="col-md-10">
                    <h2 class="text-gray mt-5">Our community</h2>
                    <p>The Coalition formed from the shared ideals of 16 companies and continues to grow as other firms join the call.</p>
                    <p><i>* = Founding member</i></p>
                </div>
            </div>

            <div class="row justify-content-md-between">
                <div class="col-md-5">
                    <MemberItem class="row mt-5" link-url="https://540.co" img="540-Logo-Primary-Black.png" img-alt="540">
                        “We believe in the value of moving fast, showing capabilities (rather than talking about them), and doing whatever it takes to make our government operate in a more effective manner. The Coalition enables us to collaborate, share ideas, and further those ideals.” <i>*</i>
                    </MemberItem>
                    
                    <MemberItem class="row mt-5" link-url="https://adhocteam.us" img="logo-adhoc.png" img-alt="Ad Hoc">
                        “We look forward to working with the coalition to make a difference in the daily lives of users through improved interactions with government digital services built specifically for them.” <i>*</i>
                    </MemberItem>
                    
                    <MemberItem class="row mt-5" link-url="https://www.agile6.com" img="logo-agilesix.png" img-alt="Agile Six">
                        “We believe that strong teams are built on trust and agility. When someone tells you that they’ve “Got Your Six,” it means they’re watching your back. Knowing other member firms have our six means we can focus on transforming the working relationship between government and the private sector — which we believe will deliver better digital experiences for our citizens.” <i>*</i>
                    </MemberItem>

                    <MemberItem class="row mt-5" link-url="https://www.awlstrategies.com/" img="AWL_Logo_Color_MAIN.png" img-alt="AWL Strategies">
                        “Our mission is great business outcomes through purpose-driven communications. We believe shared leadership creates strength, and we bring a stack of chairs with us to every table. We joined the DSC because at this table, leaders work together to make change across government fit, for everyone.”
                    </MemberItem>

                    <MemberItem class="row mt-5" link-url="https://www.bixal.com/" img="logo-bixal.png" img-alt="Bixal">
                        “We are a mission-driven organization determined to improve people’s lives through human-centered strategies and transformative technologies. We deliver on this promise by partnering with leading federal agencies to conceive and create powerful, data-driven customer experiences.”
                    </MemberItem>

                    <MemberItem class="row mt-5" link-url="https://capitaltg.com" img="logo-ctg.png" img-alt="Capital Technology Group">
                        “Working in collaboration, the government and a coalition of like-minded firms can more fully realize the goal of designing, building, and delivering the most effective and transformative digital services solutions that current technology and imagination make possible.”
                    </MemberItem>

                    <MemberItem class="row mt-5" link-url="https://civicactions.com/" img="logo-civicactions.png" img-alt="Civic Actions">
                        “We’re honored to be part of a strong network of firms who embrace the values of free and open-source software, knowledge sharing, collaboration, and contributing back while fostering a culture of openness and learning in government to build the next generation of modern public services.” <i>*</i>
                    </MemberItem>

                    <MemberItem class="row mt-5" link-url="https://www.clarityinnovates.com/" img="logo-ci.png" img-alt="Clarity Innovations">
                        “We connect people with the technology necessary to make our country, and our world, a better, safer place. Discovering the technology and understanding the need is part of that quest. We practice servant leadership, respectful dialogue, technical excellence, and supporting and trusting one another.”
                    </MemberItem>

                    <MemberItem class="row mt-5" link-url="https://coforma.io/" img="logo-coforma.png" img-alt="Coforma">
                        “We craft creative solutions and build technology products that improve the communities our clients serve. We work closely with partners, including many in this coalition, to shape digital services that people rely on, co-creating progress that serves a common purpose.” <i>*</i>
                    </MemberItem>

                    <MemberItem class="row mt-5" link-url="https://esimplicity.com/" img="eSimplicity.jpg" img-alt="eSimplicity">
                        “eSimplicity is excited to be part of the energetic and enthusiastic Digital Services Coalition to nurture and grow with the civic tech community. Our relentless drive to invent new ways that delight our users and customers never stops. Our engineers and strategists focus on using technology to totally transform the existing user and customer experience and reimagine a better experience than what exists today.”
                    </MemberItem>

                    <MemberItem class="row mt-5" link-url="https://exygy.com/" img="logo-exygy.png" img-alt="Exygy">
                        “We believe in using our skills — human-centered design, iterative agile software development, and modern product approaches — to foster healthy and resilient communities. We’re part of the coalition because we care about seeing more large-scale government services designed for inclusion, co-created with people and communities who need them most.” <i>*</i>
                    </MemberItem>

                    <MemberItem class="row mt-5" link-url="https://fearless.tech" img="logo-fearless.png" img-alt="Fearless">
                        “We believe that the government has the potential to be better, and we want to help influence that change from the ground up. Our vision is to create a world where good software powers the things that matter, so we measure our success by our positive impact on the people in our communities.” <i>*</i>
                    </MemberItem>
                    
                    <MemberItem class="row mt-5" link-url="https://www.flexion.us/" img="logo-flexion.png" img-alt="Flexion">
                        “We have the strong belief that providing exceptional, accessible, and user-centric digital capabilities to the government will improve people’s everyday lives. Partnering with other innovative, agile, and forward-thinking firms will just accelerate and magnify the difference we can make.” <i>*</i>
                    </MemberItem>

                    <MemberItem class="row mt-5" link-url="https://kindsys.us/" img="logo-kind.png" img-alt="Kind Systems">
                        “Using modern web, mobile, and data technologies combined with human-centric design, the team at Kind Systems builds approachable, fast digital services in an agile fashion based on the principles of the Digital Services Playbook and our own private sector experience.”
                    </MemberItem>
                </div>
                
                <div class="col-md-5">
                    <MemberItem class="row mt-5" link-url="https://mediabarninc.com/" img="logo-mediabarn.png" img-alt="Mediabarn">
                        “We participate in this coalition and believe in its mission because we feel the government (at all levels), and by extension all people, deserve to be served by companies who take a modern, efficient, and honest approach to providing digital goods and services.” <i>*</i>
                    </MemberItem>
                    
                    <MemberItem class="row mt-5" link-url="https://www.metrostar.com/" img="MetroStar_Logos_stacked-01.svg" img-alt="MetroStar">
                        “We believe in creating digital experiences that elevate government missions. MetroStar is full of leaders, technologists, artists, and everyone in between. We know the best teams — the ones that power change — bring together people with different backgrounds to make it happen. MetroStar is Powering Change® because of our teammates.”
                    </MemberItem>

                    <MemberItem class="row mt-5" link-url="https://www.themostudio.com/" img="logo-mo.png" img-alt="MO Studio">
                        “We believe that we can help the government ask the right questions, find the right answers, conceptualize and co-design what the experience can become, and build solutions that delight the government’s customers — the public. We don’t want to play by the rules, but change how the game is played.” <i>*</i>
                    </MemberItem>

                    <MemberItem class="row mt-5" link-url="https://www.mobomo.com/" img="logo-mobomo.png" img-alt="Mobomo">
                        “An award-winning provider of digital transformation services; combining technology expertise with digital strategy, interactive marketing, and branding accelerating our customers’ digital strategy to produce innovative applications and websites.”
                    </MemberItem>

                    <MemberItem class="row mt-5" link-url="https://www.navapbc.com/" img="logo-nava.png" img-alt="Nava Public Benefit Corporation">
                        “As a public benefit corporation, Nava is driven not just by profit, but also by our mission to build government software that well serves the American public. We are proud to be charter members of the Digital Services Coalition because our collective work shows that by putting the American people and civil servants at the center, it’s possible to radically improve how we deliver government services.” <i>*</i>
                    </MemberItem>

                    <MemberItem class="row mt-5" link-url="https://oddball.io/" img="logo-oddball.png" img-alt="Oddball">
                        “We believe this group represents a unique and new way of doing business by focusing on quality, long-term relationships and delivering value to our clients. We’re excited to be part of this mission.” <i>*</i>
                    </MemberItem>

                    <MemberItem class="row mt-5" link-url="https://pluribusdigital.com/" img="logo-pluribus.png" img-alt="Pluribus Digital">
                        “Government missions make an impact on people’s lives. Software can be the ‘force multiplier’ to execute those missions. We believe that the government deserves the best in technology and talent in order to be as effective as possible.” <i>*</i>
                    </MemberItem>

                    <MemberItem class="row mt-5" link-ul="https://goraft.tech/" img="logo-raft.jpg" img-alt="Raft LLC">
                        “Raft LLC brings radical transparency and a commitment to mission success, bridging the gap between humans and data for better, sustainable program outcomes. Inspired by the Raft Consensus Model, we are obsessed with inclusive problem solving and using technology to improve lives.”
                    </MemberItem>

                    <MemberItem class="row mt-5" link-ul="https://www.simpletechnology.io/" img="logo-simple.jpg" img-alt="Simple Technology">
                        “Simple Technology believes Government should operate at the speed of innovation. Our engineers (multi-cloud, low code, and open source) are passionate about using cloud-native technologies to automate ITOps activities and business processes so agencies can focus on the mission.”
                    </MemberItem>

                    <MemberItem class="row mt-5" link-url="https://skylight.digital/" img="logo-skylight.png" img-alt="Skylight">
                        “Our mission is to make government work in a digital world. We can’t imagine a better way of doing that than being part of an ecosystem of like-minded companies.” <i>*</i>
                    </MemberItem>

                    <MemberItem class="row mt-5" link-url="https://www.skywarditsolutions.com/" img="logo-skyward.jpg" img-alt="Skyward IT Solutions">
                        “Delivering lasting federal and state initiatives through empathy, collaboration, and innovation is our ethos. We coalesce with this highly dynamic consortium of teams to continue on the endeavors of empowering the government and driving positive change, together.”
                    </MemberItem>

                    <MemberItem class="row mt-5" link-url="https://www.thesocompany.com/" img="logo-thesocompany.png" img-alt="The So Company">
                        “We’re part of the Digital Services Coalition to extend our mission of improving services quickly, intelligently, and efficiently and to collaborate with others that want to provide these same service delivery promises. True change can’t be done alone.” <i>*</i>
                    </MemberItem>

                    <MemberItem class="row mt-5" link-url="https://truss.works/" img="logo-truss.png" img-alt="Truss">
                        “The public has come to expect more because of the digital services they effortlessly enjoy every day. We want to help bridge the gap between public expectation and government delivery by improving procurement, design, and build processes to deliver high-value, modern solutions.” <i>*</i>
                    </MemberItem>

                    <MemberItem class="row mt-5" link-url="https://wheelhousegroup.com/" img="Wheelhouse.png" img-alt="Wheelhouse Group, Inc">
                        “Digital transformation is complex and requires people-focused solutions. Our expert change leaders help federal clients do the nuanced work to prepare and engage employees and the public to enthusiastically adopt change. At Wheelhouse we move organizations from Reluctance to Results™.”
                    </MemberItem>
                </div>
            </div>
        </div>
        
        <div class="bg-gray">
            <div class="container py-5">
                <h3 class="text-gray py-3">Board Members</h3>
                <div class="row text-center">
                    <div class="col-lg col-md-4 col-6 mx-auto">
                        <img src="@/assets/board-member-dan.jpg" alt="Dan Levenson" class="img-fluid pb-4" />
                        <h6 class="text-blue">
                            Dan Levenson<br/>
                            <small class="text-gray">Agile Six</small><br/>
                            <small class="text-blue">President, Board Member</small>
                        </h6>
                    </div>
                    <div class="col-lg col-md-4 col-6 mx-auto">
                        <img src="@/assets/board-member-marc.jpg" alt="Marc Jones" class="img-fluid pb-4" />
                        <h6 class="text-blue">
                            Marc Jones<br/>
                            <small class="text-gray">CivicActions</small><br/>
                            <small class="text-blue">Secretary</small>
                        </h6>
                    </div>
                    <div class="col-lg col-md-4 col-6 mx-auto">
                        <img src="@/assets/board-member-tyra.jpg" alt="Tyra Blew" class="img-fluid pb-4" />
                        <h6 class="text-blue">
                            Tyra Blew<br/>
                            <small class="text-gray">Coforma</small><br/>
                            <small class="text-blue">Treasurer</small>
                        </h6>
                    </div>
                    <div class="col-lg col-md-4 col-6 mx-auto">
                        <img src="@/assets/board-member-sarah.jpg" alt="Sarah Ruggless" class="img-fluid pb-4" />
                        <h6 class="text-blue">
                            Sarah Ruggless<br/>
                            <small class="text-gray">Flexion</small><br/>
                            <small class="text-blue">Board Member</small>
                        </h6>
                    </div>
                    <div class="col-lg col-md-4 col-6 mx-auto">
                        <img src="@/assets/board-member-greg.jpg" alt="Greg Gershman" class="img-fluid pb-4" />
                        <h6 class="text-blue">
                            Greg Gershman<br/>
                            <small class="text-gray">Ad Hoc</small><br/>
                            <small class="text-blue">Board Member</small>
                        </h6>
                    </div>
                    <div class="col-lg col-md-4 col-6 mx-auto">
                        <img src="@/assets/board-member-eduardo.jpg" alt="Eduardo Ortiz" class="img-fluid pb-4" />
                        <h6 class="text-blue">
                            Eduardo Ortiz<br/>
                            <small class="text-gray">Coforma</small><br/>
                            <small class="text-blue">Board Member</small>
                        </h6>
                    </div>
                    <div class="col-lg col-md-4 col-6 mx-auto">
                        <img src="@/assets/board-member-jessi.jpg" alt="Jessi Bull" class="img-fluid pb-4" />
                        <h6 class="text-blue">
                            Jessi Bull<br/>
                            <small class="text-gray">Nava</small><br/>
                            <small class="text-blue">Board Member</small>
                        </h6>
                    </div>
                </div>
            </div>
        </div>
        
    </section>
</template>



<script>
import Parallax from "vue-parallaxy";
import MemberItem from "@/components/MemberItem.vue";

export default {
  components: {
    Parallax,
    MemberItem,
  },
};
</script>
