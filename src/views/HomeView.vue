<template>
    
    <div id="section-home" class="section-main">

        <div class="holder">

            <p>یکی از چالش‌هایی که افراد علاقه‌مند به برنامه‌نویسی با آن مواجه می‌شوند، انتخاب زبان برای شروع برنامه‌نویسی می‌باشد که از طرف اشخاص مختلف به آن‌ها پیشنهاد می‌شود تا برنامه‌نویسی را با آن شروع کنند، از طرفی دیگر، بحث و جدال بر سر زبان‌های برنامه‌نویسی در بین برنامه‌نویسان نیز رایج است و به‌طور خلاصه، هرکسی زبانی که بلد است را زبان برتر می‌داند و سعی دارد آن‌را در بوق و کرنا کند و در این شرایط است که یک حالت تعصبی ایجاد می‌شود و باعث رفتار های غیرمنطقی می‌شود، در این صفحه سعی می‌کنیم یک‌بار و برای همیشه این مشکل را برطرف کنیم</p>

            <ExpandableItem title="قصد شروع برنامه‌نویسی دارم" icon="icon-life-buoy" type="green">
                <template #content>
                    <p>اگر قصد شروع برنامه‌نویسی را دارید، قبل از اینکه به‌دنبال آن باشید که با چه زبانی شروع کنید، باید ابتدا پلتفرم مدنظرتان را برای برنامه‌نویسی انتخاب نمایید، چرا که برنامه‌نویسی شاخه‌های گسترده و متنوعی دارد و اگر بی‌هدف وارد آن شوید گمراه خواهید شد، به‌طور کلی در این مرحله با گزینه‌های مختلفی مواجه می‌شوید :</p>
                    
                    <ul>
                        <li>پلتفرم وب (وبسایت،‌ وب‌اپلیکیشن، خدمات آنلاین و ...)</li>
                        <li>پلتفرم موبایل (اندروید، iOS و ...)</li>
                        <li>پلتفرم دسکتاپ (ویندوز، مک، گنو/لینوکس و ...)</li>
                        <li>پلتفرم سخت‌افزار (رباتیک، IoT و ...)</li>
                    </ul>

                    <p>بعد از پیدا کردن پلتفرم مورد علاقه‌تان و کسب اطمینان از انتخاب‌تان، باید یک مسیرراه آموزشی (RoadMap) برای پلتفرم مدنظرتان انتخاب کنید و در این مرحله است که شما باید زبان مدنظرتان را انتخاب کنید و براساس آن آموزشتان را شروع کنید، زمانی که شما پلتفرم مد نظرتان را انتخاب می‌کنید، زبان های برنامه‌نویسی که می‌توانید با آن‌ها کار کنید را از یک صافی عبور می‌دهید و تعداد آن‌ها را محدودتر می‌کنید و این معمولاً نشانه خوبی‌است، در جدول زیر یک لیست تقریبی از برخی زبان‌های برنامه‌نویسی و نشانه‌گذاری که می‌توانید برای پلتفرم‌های مختلف استفاده کنید گردآوری شده‌است :</p>

                    <ul>
                        <li>وب فرانت‌اند : <chip>WASM</chip> , <chip>TypeScript</chip> , <chip>JavaScript</chip></li>
                        <li>وب بک‌اند : <chip>CSharp</chip> , <chip>Go</chip> , <chip>Ruby</chip> , <chip>Rust</chip> , <chip>JavaScript</chip> , <chip>C Plus Plus</chip> , <chip>Python</chip> , <chip>PHP</chip></li>
                        <li>اندروید : <chip>B4A</chip> , <chip>C Plus Plus</chip> , <chip>Kotlin</chip> , <chip>Java</chip></li>
                        <li>آی‌او‌اس : <chip>Objective C</chip> , <chip>Swift</chip></li>
                        <li>ویندوز : <chip>Assembly</chip> , <chip>C</chip> , <chip>C Plus Plus</chip> , <chip>CSharp</chip></li>
                        <li>گنو/لینوکس : <chip>Assembly</chip> , <chip>C</chip> , <chip>C Plus Plus</chip></li>
                        <li>مک : <chip>Assembly</chip> , <chip>C</chip> , <chip>Objective C</chip> , <chip>C Plus Plus</chip> , <chip>Swift</chip></li>
                        <li>چندسکویی دسکتاپ : <chip>JavaScript</chip> , <chip>C</chip> , <chip>Python</chip> , <chip>C Plus Plus</chip></li>
                        <li>چند سکویی موبایل : <chip>CSharp</chip> , <chip>JavaScript</chip> , <chip>Dart</chip></li>
                        <li>سخت‌افزار : <chip>Assembly</chip> , <chip>C Plus Plus</chip> , <chip>C</chip></li>
                    </ul>

                    <p>زبان‌های لیست شده در بالا، صرفا برخی از زبان‌هایی هستند که شما می‌توانید در پلتفرم‌های مربوطه استفاده کنید، بی‌نهایت زبان دیگر نیز می‌توانند وجود داشته باشند که ساختار متفاوتی دارند و بتوانیم با آن برای پلتفرم‌های مختلف برنامه‌نویسی کنیم، چرا که معمولا تنها زحمت ایجاد یک زبان جدید، نوشتن یک کامپایلر یا مفسر برای آن است، در نتیجه بیشتر سعی کنید با منطق و مفهوم برنامه‌نویسی آشنا شوید و صرفا سینتکس یک زبان خاص را حفظ نکنید، یا به‌عبارت ساده‌تر، سعی کنید برنامه‌نویسی باشید، صرفا سینتکس‌نویس نباشید (:</p>

                    <p>درنهایت، یک زبان را متناسب با نیازتان انتخاب کنید و شروع کنید، نگران این نباشید که آیا زبانی که انتخاب کرده‌ام خوب است یا وقت‌تلف کردن است یا ...، چرا که درنهایت، تمامی زبان‌های برنامه‌نویسی به یکدیگر مرتبط‌اند و هیچ زبانی بی‌ربط به زبان دیگر نیست، تمامی زبان‌ها به شما منطق برنامه‌نویسی و برنامه‌نویس بودن را یاد می‌دهند و ذهن شما را برای یادگیری آسان سایر زبان‌ها آماده‌سازی می‌کنند، یادگیری هیچ‌زبانی وقت‌تلف کردن نیست! هر زبانی که یاد بگیرید و هر زبانی که بلد باشید درنهایت به شما کمک می‌کند تا زبان‌های دیگر را سریع‌تر و عمیق‌تر یاد بگیرید</p>

                    <p>مشکلی که اکثریت افراد با آن مواجه هستند، انتخاب زبان نیست، بلکه شروع نکردن است! دقیقا مثل این هست که مدت زیادی را برای مطالعه کتاب درمورد آموزش شنا بگذرانیم، این کار هیچ‌وقت از ما یک شناگر نمی‌سازد تا زمانی که به‌صورت عملی خودمان را به آب بزنیم و شروع کنیم، در کل سعی کنید زیاد نگران مسیر و زبان نباشید و این موارد را برای خودتون بهانه نکنید، هرچه سریع‌تر شروع کنید</p>

                    <p>همچنین لطفا بعد از اینکه شروع به یادگیری یک زبان کردید، شاخه‌به‌شاخه نشوید! یکی از مشکلاتی که باعث عدم تمرکز و یادگیری شما می‌شود، شاخه‌به‌شاخه شدن است، دلیل این مورد، احتمالا به دلیلِ مطمئن نبودن از مسیر یا هیجانات زودگذر یا عدم شناخت و علاقه به پلتفرم باشد که نتیجه‌اش چیزی جز فاجعه نیست، تا حدامکان سعی کنید هیچ‌وقت تا زمانی که در یک زبان یا شاخه به حد متوسط به بالا نرسیدید، به شاخه دیگری نپرید</p>
                    
                    <p>در نهایت، هرگونه آموزشی که می‌بینید یا کتابی که می‌خوانید یا در دوره‌ای شرکت می‌کنید، به تمرینات آن‌ها اکتفا نکنید و خودتان تمرین بزنید ! هیچ‌کسی نمی‌تونه چیزی به شما یاد دهد، در کل، چیزی به نامِ یاد دادن وجود ندارد! ولی یاد گرفتن چرا! آدم‌ها با محصولی که خودشان خلق می‌کنند یاد می‌گیرند، نه با گفته‌ها و بیانات یک شخص دیگر، سعی کنید هرچیزی که آموزش می‌بینید را خودتان به‌شکلی دیگر پیاده‌سازی کنید و البته محصولی از خلاقیت ذهن خودتان را پیاده کنید، نه صرفا کپی از چیزی که استاد آموزش داده، در این شرایط است که آموزش‌های شما از حافظه کوتاه‌مدت‌تان به حافظه بلندمدت‌تان منتقل خواهد شد و یادگیری شما تکمیل می‌شود</p>
                </template>
            </ExpandableItem>

            <hr>

            <ExpandableItem title="برنامه‌نویس هستم" icon="icon-figma" type="blue">
                <template #content>
                    <p>اگر برنامه‌نویس هستید،‌ این احتمال وجود دارد که با یک زبانی کار کرده باشید و در آن حرفه‌ای شده باشید و از طرفی حوصله یادگیری زبان های جدید را نداشته باشید، در چنین شرایطی، شما دچار تعصب یا Bias نسبت به آن زبان می‌شوید و این اصلا نشانه خوبی نیست</p>

                    <p>زمانی که دچار یک Bias نسبت به یک پدیده‌ای باشیم، معمولا با دیدگاه منطقی به ماجرا نگاه نمی‌کنیم و همیشه به‌صورت جانب‌دارانه بحث می‌کنیم که باعث کم‌رنگ‌تر شدن قوه منطق‌مان در بحث‌ها می‌شود، به‌صورت ناخودآگاه از زبانی که به آن تعصب داریم در بحث‌ها دفاع می‌کنیم و سعی می‌کنیم بقیه را متقاعد کنیم که : ای جماعت، شما همگی اشتباه می‌کنید و مسیر اشتباهی می‌روید، فقط مسیر من درست هست که با این زبان کار می‌کنم !</p>

                    <p>چنین بحث‌هایی معمولا نه‌تنها به نتیجه مطلوبی ختم نمی‌شوند بلکه باعث اتلاف وقت تمامی مشارکت‌کنندگان و همچنین ایجاد کینه می‌شوند که معمولا نتیجه جالبی هم به‌همراه ندارد</p>

                    <p>به‌طور کلی اگر زبانی خوب است، سعی کنید خودتان استفاده کنید و از پیشنهاد دادن به بقیه پرهیز کنید، در حوزه برنامه‌نویسی معمولا امر به معروف اقدام جالبی محسوب نمی‌شود و به این‌صورت تلقی می‌شود که مسیر من درست است و مسیر شما اشتباه.‌ بیایید از مسیر من برویم</p>

                    <p>هر زبان برنامه‌نویسی که وجود دارد، با یک هدف و استدلال و منطق مشخصی ایجاد شده‌است و هیچ زبانی وجود ندارد که بر سر کامل و بی‌نقص بودن آن توافق و اجماع وجود داشته‌باشد، یک‌نفر دوست دارد مستقیما و با کم‌ترین کد اضافه برای سیستم برنامه‌نویسی کند و سراغ <chip>Assembly</chip> می‌رود و یک‌نفر دیگر دوست دارد به ساده‌ترین حالت ممکن و در سریع‌ترین زمان برنامه خود را بنویسید و دغدغه‌اش این نیست که برنامه‌ام چند کیلوبایت منابع کم‌تری مصرف کند، در نتیجه سراغ <chip>Python</chip> می‌رود</p>

                    <p>به‌صورت کلی، معیار های انسان‌ها برای انتخاب بهترین زبان برنامه‌نویسی متفاوت است، به‌همین دلیل، معمولا نمی‌توانیم به اجماع برسیم، یک‌نفر بهترین زبان برنامه‌نویسی را ساده‌ترین زبان برنامه‌نویسی می‌داند و ‌نفر دیگر، سریع‌ترین و آن یکی، کم‌حجم‌ترین؛ و این حلقه تا بی‌نهایت ادامه دارد، در حالت کلی یک کد بهینه نوشته شده به یک زبان، از یک کد غیربهینه نوشته شده به یک زبان دیگر، چندین برابر بهتر است، مهم نیست که ما چه زبانی استفاده می‌کنیم، مهم این است که با آن زبان چه چیزهایی خلق می‌کنیم</p>

                    <p>به‌صورت خلاصه، بهتر است که روی زبان خاصی تعصب نداشته باشیم، چرا که تمامی زبان‌ها برای کارهای مشخصی عملکرد مطلوبی دارند و هیچ‌زبانی نمی‌تواند تمامی مشخصه‌های ایده‌آل بودن را داشته باشد، همچنین در پروژه‌هایی که انجام می‌دهیم ابتدا یک نیازسنجی عمومی درمورد پروژه داشته باشیم و بر‌اساس نیاز پروژه اقدام به انتخاب زبان مناسب کنیم، نه لزوما زبانی که خودمان بلد هستیم را در هر شرایطی برای هر پروژه‌ای استفاده کنیم (:</p>
                </template>
            </ExpandableItem>

            <hr>

            <p>به‌طور خلاصه، یادگیری هیچ زبانی خالی از لطف نیست و تمامی زبان‌های برنامه‌نویسی در جای خودشان کاربردی هستند، چرا که اگر یک زبانِ کامل وجود داشت، دلیلی برای ایجاد سایر زبان‌ها نبود؛ پس سعی کنیم به جای تعصب بی‌جا بر روی یک زبان، با نقاط قوط و ضعف تمامی زبان‌های برنامه‌نویسی مرسوم آشنا شویم و با توجه به نیازمندی‌های پروژه‌ای که انجام می‌دهیم، زبان ایده‌آل را برای انجام آن انتخاب کنیم</p>

        </div>

    </div>

</template>

<script>
import ExpandableItem from '@/components/Expandable.vue';

export default {
    name: 'HomeView',
    components: {
        ExpandableItem,
    }
}
</script>
