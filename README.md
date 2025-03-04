# Finetuning-DeepSeek-R1

- Performance ကောင်းကြောင်း ပြသလိုခြင်း မဟုတ်ပါ။
- ကိုယ်ပိုင် dataset တစ်ခုကို အသုံးပြုပြီး LLM finetuning လုပ်နိုင်တာကို သိစေချင်တာ ဖြစ်ပါတယ်။

လက်ရှိ ကျွန်တော်တို့ personal computer တွေရဲ့ computing resource အရ LLM model တစ်ခုကို ကိုယ်ပိုင် train ယူဖို့ နေနေသာသာ finetuning လုပ်ယူဖို့တောင် မလွယ်ကူလှပါဘူး။
အခုလည်း ကျွန်တော်အနေနဲ့ Distill model လေးတွေကိုသာ finetuning လုပ်ပြနိုင်တာ ဖြစ်ပါတယ်။ ဒါတောင် အနည်းဆုံး batch size နဲ့ colab gpu ကို သုံးခဲ့ရတာပါ။

Distill model တွေသည် မူလ based model ရဲ့ performance ကို parameter အရသော်လည်းကောင်း၊ quantization အရသော်လည်းကောင်း အများကြီး လျှော့ချပေးထားပါတယ်။
ဒါတောင် DeepSeep ရဲ့ အသေးဆုံး Distill model သည် 1.5B parameters ရှိနေပါသေးတယ်။

ဘာပဲ ပြောပြော... ကျွန်တော်တို့ အနေနဲ့တော့ Distill model လေးတွေကို သုံးပြီး LLM model တွေကို finetuning လုပ်ဖူးသွားတာပေါ့ဗျာ။

DeepSeep ဆိုရင် 671B parameters ရှိပြီး Activated Parameters အနေနဲ့တောင် 37B ရှိပါတယ်။ 
ဒီ parameter လောက်ကို train နိုင်ဖို့ အတွက် ဆိုရင်တောင် ကျွန်တော်တို့မှာ memory ≈444 GB လောက် လိုနေပါသေးတယ်။

ဒါကြောင့် ဒီလို model မျိုးကို သာမန် computer တစ်လုံးရဲ့ ဘယ်လိုမှ ချဉ်းကပ်လို့ မရနိုင်ပါဘူး။
အောက်မှာ LLM model တစ်ခုကို train ယူဖို့ လိုအပ်တဲ့ memory usage လေးတွေကို လေ့လာကြည့်နိုင်ပါတယ်။

![Result](https://github.com/Ko-Yin-Maung/Finetuning-DeepSeek-R1/blob/main/Memory%20Calc.png)

(လေ့လာခြင်းဖြင့် ကျွန်ုပ်တို့၏ မနက်ဖြန်များကို ဖြတ်သန်းကြပါစို့..။)

@Created by Myanmar Innovative Group (MIG)
