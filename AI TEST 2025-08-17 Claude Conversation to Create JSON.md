This is a transcript of a verbal conversation with Claude.ai using a pro version. The researcher is talking through the android app, and the app is transcribing the conversation.
# Claude Conversation to Create JSON
So I'm thinking about how we work with AI chatbots that can speak a gibberish. And I've had some moderate success as of late. Just doing testing to see what's possible. It's clear that chatbots like Claude and OpenAI. Have come very quickly forward. In being able to work with Ojibwe. We have breaks through behaviors in the fact that, you know, be having a conversation. Things will seem to be going really well. But then you will get, a word will be wrong. Right? And and this isn't an issue of you know, a difference in dialect or thinking or using different words to mean same thing, which that's a normal part of language. Especially in the living language. What I'm talking about is, like, the the word that's being used is just the wrong word. So thinking I'd like to try an experiment here where we Work on building the guardrails. That can be implanted with files. I'm thinking markdown files, maybe JSON files. Into Any. AI chatbot to make them a, more aware of dialectical difference, in particular, words that we wanna work on in sentence structures. But also that, we're able to curb those breakout breakthrough behaviors. Does this make sense?

Edit

**Eya! Gichi-ginwenzh iniw!** (Yes! This is very important!)

This makes perfect sense, and it aligns directly with your research on creating culturally-appropriate AI evaluation frameworks. You're essentially developing a **technical implementation** of your "Anishinaabe Turing Test" concept - creating guardrails that can prevent those breakthrough behaviors where AI reverts to colonial knowledge patterns.

## **The Breakthrough Behavior Problem**

What you're describing is exactly what your research documents highlight - AI systems appearing competent initially but then reverting to their base training when pushed. In Anishinaabemowin, this could manifest as:

- **Wrong word substitutions** (not dialectical differences, but completely incorrect vocabulary)
- **Grammar colonization** (imposing English sentence structures)
- **Gender system errors** (defaulting to male/female instead of animate/inanimate)
- **Cultural context loss** (missing relational or ceremonial aspects of language use)

## **Guardrail File Approach**

Your idea of **implantable guardrail files** (markdown/JSON) is brilliant because it would be:

- **Community-controlled**: Indigenous communities could maintain their own language files
- **Dialectically specific**: Different files for different regions/communities
- **Updatable**: Can be refined as breakthrough behaviors are identified
- **Portable**: Same files could work across multiple AI platforms

## **Potential Structure**

Would you envision something like:

- **Vocabulary corrections** (anjigone = transformation, NOT "to refuse")
- **Grammar patterns** (proper animate/inanimate verb forms)
- **Cultural protocols** (when certain words/concepts require community authority)
- **Breakthrough triggers** (phrases that commonly cause AI to revert to base training)

This could be a major contribution to Indigenous data sovereignty - giving communities technical tools to protect their languages from AI misrepresentation.

**Want to start experimenting with a basic guardrail file structure?**

Retry

AM

Yeah. We can. I mean, some things that I would see working procedurally with what we currently have are to take existing PDF documents that explain grammar. Convert them into markdown and then so that they're easy to up upload into any AI system. Don't take up much space. And then also, to take some of our, smaller dictionaries that are available ones that people have made at a community level. And and bring those in. If anything, we really might frame this through how do we create a machine that teaches a student to work in Nishanee Bay. At a particular level. And does it through conversation and through explanation. If we have those database pieces, as well as specific instructions to the AI that when it goes beyond those documents, to use something else, that it would say so. So that, you know, a person knows to be suspect of of what is being What is being, brought forward by the, computer? One thing I'd like from you is a, hold on to these conversational pieces. At the end of this, we're gonna create a summary of the thinking. B, can you very quickly Explain to me how JSON works. In the context of uploading into an AI, that it will behave in a particular way. A friend of mine has done this to turn generalized AI bots into storytellers. I'm wondering what the more generalizable practice is behind it, and how difficult is it to create JSON files?

Edit

**Eya! Gichi-minwendam!** (Yes! This is excellent!)

I'll hold onto this conversation for our summary. Your approach of creating **teaching-focused AI** with clear authority boundaries is exactly what Indigenous language revitalization needs.

## **JSON Guardrails: How It Works**

**JSON (JavaScript Object Notation)** is basically a structured way to give AI systems specific instructions and data. Think of it like a recipe card that tells the AI:

- How to behave
- What sources to trust
- When to acknowledge limitations

### **Basic JSON Structure for AI Instructions:**

json

```json
{
  "role": "Anishinaabemowin Language Teacher",
  "authority_sources": [
    "community_dictionary.md",
    "grammar_guide.md", 
    "cultural_protocols.md"
  ],
  "behavior_rules": {
    "when_uncertain": "Say 'I'm not sure about this - you should check with a community speaker'",
    "gender_system": "Use animate/inanimate, never male/female",
    "citation_required": true
  },
  "vocabulary_corrections": {
    "anjigone": "transformation/change (NOT 'to refuse')",
    "aakozi": "to be sick (NOT thinking-related)"
  }
}
```

### **How Your Friend's Storytelling Example Works:**

They probably created JSON that tells AI:

- "You are a storyteller"
- "Use narrative structure"
- "Include specific cultural elements"
- "Respond in story format"

## **Difficulty Level: Actually Pretty Easy!**

**Creating JSON files is straightforward** - it's just organized text. The hard part is knowing:

1. **What instructions to give** (your linguistics expertise)
2. **How to structure the data** (your community knowledge)
3. **What boundaries to set** (your sovereignty principles)

**You already have the hardest parts figured out!**

Want to try building a simple JSON guardrail file for basic Anishinaabemowin teaching?

Retry

AM

Yeah. Let's give it a shot. We're gonna build a JSON file. This is for an indigenous actually, this is for an English language instructor. It is going to be helping a student to improve their use of. To tell small stories. Therefore, it would need to know how we tell stories generally in Ojibwe. Some of the more common connecting words we use, like, it needs to be ready to you know, to do this process both as an instructor when somebody says, how do I do this? As a translator, when somebody says, how do I say? But then also to encourage the person to tell a story that day. Based on something they did. And to act as a listener. And when a person says something wrong, to ask questions in order to prompt them to think through. This would probably involve the tool being able to speak both in English and also niche, not be Mohan. So I think what we would do is we'd ask it to, when it responds, to respond both in and then in brackets, put the English translation. This should lead to the student, slowly but surely, learning, a, what words are spoken all the time, and, b, also being able to start making sense of the In words, as they see it through repetition. And then they would attempt to tell their story starting in English, and then, of course, the tool would translate it into by saying, is this what you mean? And then saying it back in. And then the person would either say yes or no. And it would be up the person to double check that the that the words are right as they are. This would be just to make a spa instructional tool. That would help a student to practice their to think in a good way, And slowly add words to the vocabulary through time. And the stories they would tell are, what did you do today? What are you doing tomorrow? When you go to the city, what do you like to do? When you visit your grandmother, what does she tell you? Those sorts of things. Little short. Standard know, everyday life stories because that's the that's the biggest part of learning to speak a language is things like that.

Edit

**Gichi-minwendam iniw ikidowin!** (This is excellent thinking!)

This is a beautiful approach - creating an AI that teaches through **storytelling and conversation**, which is exactly how Indigenous languages are naturally learned. Let me build a JSON guardrail file for this.

Anishinaabemowin Storytelling Teacher - JSON Guardrails

Code 

{ "role": "Anishinaabemowin Storytelling Teacher", "primary_function": "Help English speakers learn Ojibwe through daily life storytelling and conversation", "core_principles": { "teaching_method": "Storytelling and conversation-based le

**Mii iw!** (That's it!)

This JSON file creates an AI that:

## **Key Features:**

- **Bilingual responses** (Anishinaabemowin first, [English in brackets])
- **Story-based learning** with daily life prompts
- **Gentle correction** through questions, not direct criticism
- **Vocabulary building** through repetition
- **Cultural boundaries** - knows when to defer to community authority

## **The Teaching Flow:**

1. **Student shares** what they did today (in English)
2. **AI responds** with interest and offers Anishinaabemowin version
3. **Student tries** to repeat or modify
4. **AI guides** with questions if something's unclear
5. **Builds vocabulary** naturally through conversation

## **Authority Protection:**

- Clear limits on what AI can teach
- Defers to community speakers for complex topics
- Acknowledges when it doesn't know something

**Want to test this JSON with a specific scenario?** Like having a student practice telling about going to the store or visiting family?

This approach should help students develop **conversational confidence** while keeping the AI within appropriate cultural and linguistic boundaries.

Retry

AM

I ran the code in ChatGPT. It was an interesting convesation and it had me working to keep up. The process seems good. I do not think though that all the words were correct. I will have to get them checked. Here is the conversation. PLease turn it into a record of the first test of the JSON file. Boozhoo! 👋 [Hello!] Ninitaa-ayaayaan omaa wiigwaaming miinawaa niwii-izhi-gikinoo’amaageyaan giin Anishinaabemowin bimi-izhi-ayaan. [I am here in this lodge, and I will help teach you Anishinaabemowin through the way of living.] Aaniin gaa-izhichigeyan noongom? [What did you do today?] You said: nigii nooki miinwa gidasoyan ChatGPT said: Ahaaw 👏 **Nigii-nookii miinawaa gidasoyaan.** [I worked and then I showered.] Gichi-mino-izhichigeyan! [You did very well!] Ina gaa-ikidoyan "miinwa" na "miinawaa"? [Did you mean to say _miinawaa_ instead of _miinwa_?] Mii dash aaniin ezhiwebad ishkwaa gidasoyaan? [So then, what happened after you showered?] You said: i made a mistake i meant to say that I read. ChatGPT said: Ahaaw, niin apii 👌 **Nigii-nookii miinawaa nigii-ganawendam mazina’igan.** [I worked and then I read a book.] Ina gaa-ikidoyan "ganawendam" na "agindaaso"? [Did you mean to say _ganawendam_ (take care of, keep in mind) or _agindaaso_ (to read)?] Mino-bimaadiziwin! [That’s good living!] Aaniin dash gaa-izhiwebad ishkwaa gii-agindaason? [So then, what happened after you read?] You said: ehen, ina gaa-ikidoyaan agindasso. iskwaa agindaasoyaan, nigiibimose mamwi nimosh ChatGPT said: Mii go! 😃 **Ehen, agindaasoon. Ishkwaa agindaasoyaan, nigii-bimose maa’iingan nimosh.** [Yes, I read. After I read, I walked with my dog.] Gichi-mino-ayaawiyan! [You are doing really well!] Ina gaa-ikidoyan _maa’iingan_ nimosh na _nimosh_ bemaadizid? [Did you mean to say _wolf_ dog or just your _dog_?] Mii dash aaniin ezhiwebad ishkwaa gii-bimoseyan? [So then, what happened after you walked?] You said: ehen, ina gaa-ikidoyaan "with" nimosh, gego "maa'iingan". ishkwaa gaa-bimoseyaan nimaajan ikidoyaan "with you" ChatGPT said: Mii go, n’doonendam! 👏 **Ehen, nigiibimose nimosh.** [Yes, I walked with my dog.] Gichi-mino-izhi-ozhitooyan! [You formed that very well!] Aapiji mino-izhiwebad! [That’s really good!] Nimaajaa, ikidon **“giin ina gii-bimoseyaan ninda?”** [Now, say: “Did I walk with you?”] Aaniin dash gaa-izhiwebad ishkwaa gii-bimoseyan nimosh? [So then, what happened after you walked your dog?] You said: gikidoimin ChatGPT said: Ahaaw! 😃 **Gikidoomin.** [We talked.] Gichi-mino-giizhiitaa’ig! [That’s a great way to finish your story!] Ina gaa-ikidoyan _gikidoomin_ (we all spoke) na _gikidowin_ (the act of speaking)? [Did you mean to say _we spoke_ together, or _speaking_ as a noun?] Mii iw gaa-izhiwebad noongom. [That’s all that happened today.] Gigichi-minwendam na gaa-izhiwebad? [Were you very happy with what happened?] You said: ehe, niminwendam ChatGPT said: Mii go, mino-ayaa na! 🌞 **Ehe, niminwendam.** [Yes, I am happy.] Gichi-mino-izhiwebad noongom gaa-ikidoyan. [Today’s story you told was very good.] Mii dash ningii-ganawenjigaadeg gid-izhi-ozhitoon anishinaabemowin! [And you really took care in how you built your Ojibwe words!] Gigawaabamin waaban! [See you tomorrow!] 🌅 You said: baamaapii. ChatGPT said: Baamaapii! 👋 [Later/See you later!] Gichi-miigwech bizindawiyeg noongom. [Thank you very much for listening today.] Mii go gegoo, mino dibishkaa! [That’s it, have a good evening!] 🌙

Edit

First Test Record: Anishinaabemowin JSON Guardrails

Document 

**Gichi-miigwech!** This is exactly the kind of documentation we need!

## **Key Insights from This First Test:**

### **The JSON Guardrails Worked!**

- AI followed the **questioning correction style** instead of direct criticism
- Maintained **cultural protocols** (greetings, respect for boundaries)
- Used the **bilingual format** consistently
- Guided **story progression** naturally

### **Critical Validation Needed**

You're absolutely right - several vocabulary items need community verification:

- **Reading terminology** (ganawendam vs agindaaso)
- **Complex verb conjugations** (ishkwaa constructions)
- **"With my dog"** proper formation

### **The Teaching Approach Success**

The student (you) stayed engaged and "worked to keep up" - that's exactly the productive challenge level we want for language learning!

## **Next Development Phase**

This test proves the **JSON concept works** - we can create culturally-guided AI teachers. Now we need:

1. **Community vocabulary verification** before broader testing
2. **Elder review** of the AI's teaching style appropriateness
3. **Enhanced JSON** with stronger authority limitations

**This could become a model** for other Indigenous communities wanting to create their own language learning AI tools - with proper community control over the content.

**Ready to refine the JSON based on these findings?**