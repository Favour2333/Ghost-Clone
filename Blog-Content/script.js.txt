const clickBtn = document.getElementById('click-btn');
const portalWrap = document.querySelector('.portal-wrapper');
const cancelBtn = document.getElementById('cancel-btn');
const clickBtn1 = document.getElementById('click-btn-1');
const portalWrap1 = document.querySelector('.portal-wrapper-1');
const cancelBtn1 = document.getElementById('cancel-btn-1');

clickBtn.addEventListener("click", function() {
    portalWrap.style.display = 'block';
    portalWrap1.style.display = 'none';
});

cancelBtn.addEventListener("click", function() {
    portalWrap.style.display = 'none';
});

clickBtn1.addEventListener("click", function() {
    portalWrap1.style.display = 'block';
    portalWrap.style.display = 'none';
});

cancelBtn1.addEventListener("click", function() {
    portalWrap1.style.display = 'none';
});

// Headers Clickable //

const proBtn = document.getElementById('pro-btn');
const proContainer = document.querySelector('.pro-container');
const proCancelBtn = document.getElementById('pro-cancel-btn');
const solBtn = document.getElementById('solution-btn');
const solContainer = document.querySelector('.sol-container');
const solCancelBtn = document.getElementById('sol-cancel-btn');
const supportBtn = document.getElementById('support-btn');
const supportContainer = document.querySelector('.sup-container');
const supCancelBtn = document.getElementById('sup-cancel-btn');
const companyBtn = document.getElementById('company-btn');
const companyContainer = document.querySelector('.com-container');
const companyCancelBtn = document.getElementById('com-cancel-btn');
const howBtn = document.getElementById('how-btn');
const howContainer = document.querySelector('.ho-container');
const howCancelBtn = document.getElementById('ho-cancel-btn');


proBtn.addEventListener("click", function() {
    proContainer.style.display = 'block';
    document.body.style.overflow = 'hidden';
    solContainer.style.display = 'none';
    supportContainer.style.display = 'none'
    companyContainer.style.display = 'none'
    howContainer.style.display = 'none'

    ITELfullEl.style.display = 'none'; // All 5 here are solution full element products //
    DatafullEl.style.display = 'none';
    EnfullEl.style.display = 'none';
    EnStofullEl.style.display = 'none';
    EnSoftfullEl.style.display = 'none';

    ChoosefullEl.style.display = 'none'; // All 6 here are Support and Servies element product //
    DocumentfullEl.style.display = 'none';
    ProfessionalfullEl.style.display = 'none';
    EducationfullEl.style.display = 'none';
    SymantecfullEl.style.display = 'none';
    SoftwarefullEl.style.display = 'none';

    AboutfullEl.style.display = 'none';  // All 3 here are Company elements products //
    BlogfullEl.style.display = 'none';
    ContactfullEl.style.display = 'none';

    HardwarefullEl.style.display = 'none'; // How-to-buy elements products //

});

proCancelBtn.addEventListener("click", function() {
    proContainer.style.display = "none";

    proFullEl.style.display = 'none'; // All 4 here are product full element products //
    wireFullEll.style.display = 'none';
    connectFullEl.style.display = 'none';
    OpticalfullEl.style.display = 'none';
    ITCOMfullEl.style.display = 'none';

    document.body.style.overflowX = 'hidden';
    document.body.style.overflowY = 'scroll';
});

solBtn.addEventListener("click", function() {
    solContainer.style.display = 'block';
    supportContainer.style.display = 'none';
    proContainer.style.display = 'none';
    companyContainer.style.display = 'none'
    howContainer.style.display = 'none'

    document.body.style.overflow = 'hidden';


    proFullEl.style.display = 'none';   // All 5 here are product full element products //
    wireFullEll.style.display = 'none';
    connectFullEl.style.display = 'none';
    OpticalfullEl.style.display = 'none';
    ITCOMfullEl.style.display = 'none';

    ChoosefullEl.style.display = 'none'; // All 6 here are Support and Servies element product //
    DocumentfullEl.style.display = 'none';
    ProfessionalfullEl.style.display = 'none';
    EducationfullEl.style.display = 'none';
    SymantecfullEl.style.display = 'none';
    SoftwarefullEl.style.display = 'none';

    AboutfullEl.style.display = 'none';  // All 3 here are Company elements products //
    BlogfullEl.style.display = 'none';
    ContactfullEl.style.display = 'none';

    HardwarefullEl.style.display = 'none'; // How-to-buy elements products //
});

solCancelBtn.addEventListener("click", function() {
    solContainer.style.display = "none";

    ITELfullEl.style.display = 'none';   // All 4 here are solution full element products //
    DatafullEl.style.display = 'none';
    EnfullEl.style.display = 'none';
    EnStofullEl.style.display = 'none';
    EnSoftfullEl.style.display = 'none';

    document.body.style.overflowX = 'hidden';
    document.body.style.overflowY = 'scroll';
});

supportBtn.addEventListener("click", function() {
    supportContainer.style.display = 'block';
    solContainer.style.display = 'none';
    proContainer.style.display = 'none';
    companyContainer.style.display = 'none'
    howContainer.style.display = 'none'

    proFullEl.style.display = 'none';   // All 5 here are product full element products //
    wireFullEll.style.display = 'none';
    connectFullEl.style.display = 'none';
    OpticalfullEl.style.display = 'none';
    ITCOMfullEl.style.display = 'none';

    ITELfullEl.style.display = 'none';   // All 4 here are solution full element products //
    DatafullEl.style.display = 'none';
    EnfullEl.style.display = 'none';
    EnStofullEl.style.display = 'none';
    EnSoftfullEl.style.display = 'none';  
    
    AboutfullEl.style.display = 'none';  // All 3 here are Company elements products //
    BlogfullEl.style.display = 'none';
    ContactfullEl.style.display = 'none';

    HardwarefullEl.style.display = 'none'; // How-to-buy elements products //

    document.body.style.overflow = 'hidden';
});

supCancelBtn.addEventListener("click", function() {
    supportContainer.style.display = 'none'

    ChoosefullEl.style.display = 'none'; // All 6 here are Support and Servies element product //
    DocumentfullEl.style.display = 'none';
    ProfessionalfullEl.style.display = 'none';
    EducationfullEl.style.display = 'none';
    SymantecfullEl.style.display = 'none';
    SoftwarefullEl.style.display = 'none';

    document.body.style.overflowX = 'hidden';
    document.body.style.overflowY = 'scroll';
});

companyBtn.addEventListener("click", function() {
    companyContainer.style.display = 'block';
    supportContainer.style.display = 'none';
    solContainer.style.display = 'none';
    proContainer.style.display = 'none';
    howContainer.style.display = 'none'

    proFullEl.style.display = 'none';   // All 5 here are product full element products //
    wireFullEll.style.display = 'none';
    connectFullEl.style.display = 'none';
    OpticalfullEl.style.display = 'none';
    ITCOMfullEl.style.display = 'none';

    ITELfullEl.style.display = 'none';   // All 4 here are solution full element products //
    DatafullEl.style.display = 'none';
    EnfullEl.style.display = 'none';
    EnStofullEl.style.display = 'none';
    EnSoftfullEl.style.display = 'none'; 

    ChoosefullEl.style.display = 'none'; // All 6 here are Support and Servies element products //
    DocumentfullEl.style.display = 'none';
    ProfessionalfullEl.style.display = 'none';
    EducationfullEl.style.display = 'none';
    SymantecfullEl.style.display = 'none';
    SoftwarefullEl.style.display = 'none';

    HardwarefullEl.style.display = 'none'; // How-to-buy elements products //

    document.body.style.overflow = 'hidden';
});

companyCancelBtn.addEventListener("click", function() {
    companyContainer.style.display = 'none'
    
    AboutfullEl.style.display = 'none';  // All 3 here are Company elements products //
    BlogfullEl.style.display = 'none';
    ContactfullEl.style.display = 'none';

    document.body.style.overflowX = 'hidden';
    document.body.style.overflowY = 'scroll';
});

howBtn.addEventListener("click", function() {
    howContainer.style.display = 'block';
    companyContainer.style.display = 'none';
    supportContainer.style.display = 'none';
    solContainer.style.display = 'none';
    proContainer.style.display = 'none';

    proFullEl.style.display = 'none';   // All 6 here are product full element products //
    proContainer.style.display = 'none';
    wireFullEll.style.display = 'none';
    connectFullEl.style.display = 'none';
    OpticalfullEl.style.display = 'none';
    ITCOMfullEl.style.display = 'none';

    ITELfullEl.style.display = 'none';   // All 4 here are solution full element products //
    DatafullEl.style.display = 'none';
    EnfullEl.style.display = 'none';
    EnStofullEl.style.display = 'none';
    EnSoftfullEl.style.display = 'none'; 

    ChoosefullEl.style.display = 'none'; // All 6 here are Support and Servies element products //
    DocumentfullEl.style.display = 'none';
    ProfessionalfullEl.style.display = 'none';
    EducationfullEl.style.display = 'none';
    SymantecfullEl.style.display = 'none';
    SoftwarefullEl.style.display = 'none';

    AboutfullEl.style.display = 'none';  // All 3 here are Company elements products //
    BlogfullEl.style.display = 'none';
    ContactfullEl.style.display = 'none';

    document.body.style.overflow = 'hidden';
});

howCancelBtn.addEventListener("click", function() {
    howContainer.style.display = 'none'
    
    HardwarefullEl.style.display = 'none'; // How-to-buy elements products //

    document.body.style.overflowX = 'hidden';
    document.body.style.overflowY = 'scroll';
});

// Products Clickable //

let Active = document.querySelector('.active')
const proEl = document.getElementById('pro-EL');
let closeBtn = document.getElementById('close-btn');
const proFullEl = document.querySelector('.pro-full-El');
let wireCloseBtn = document.getElementById('wire-close-btn');
const wireEl = document.getElementById('wireless-El');
const wireFullEll = document.querySelector('.wire-full-El');
const Connect = document.getElementById('Connect');
const connectFullEl = document.querySelector('.Connect-full-El');
let connectCloseBtn = document.getElementById('Connect-close-btn');
const Optical = document.getElementById('Optical');
const OpticalfullEl = document.querySelector('.Optical-full-El')
let OpticalCloseBtn = document.getElementById('Optical-close-btn')
const ITCOM = document.getElementById('IT-com');
const ITCOMfullEl = document.querySelector('.IT-com-full-El')
let ITCOMCloseBtn = document.getElementById('IT-com-close-btn')

proEl.addEventListener("click", function() {
    proFullEl.style.display = 'block'; 
    wireFullEll.style.display = 'none';
    connectFullEl.style.display = 'none';
    OpticalfullEl.style.display = 'none';
    ITCOMfullEl.style.display = 'none';
});

closeBtn.addEventListener("click", function() {
    wireFullEll.style.display = 'none';
    proFullEl.style.display = 'none';
    connectFullEl.style.display = 'none';
    ITCOMfullEl.style.display = 'none';
});

wireCloseBtn.addEventListener("click", function() {
    wireFullEll.style.display = 'none';
    proFullEl.style.display = 'none';
    connectFullEl.style.display = 'none';
    OpticalfullEl.style.display = 'none';
    ITCOMfullEl.style.display = 'none';
});


wireEl.addEventListener("click", function() {
    wireFullEll.style.display = 'block';
    proFullEl.style.display = 'none';
    connectFullEl.style.display = 'none';
    OpticalfullEl.style.display = 'none';
    ITCOMfullEl.style.display = 'none';
});

Connect.addEventListener("click", function() {
    connectFullEl.style.display = 'block';
    proFullEl.style.display = 'none';
    wireFullEll.style.display = 'none';
    OpticalfullEl.style.display = 'none';
    ITCOMfullEl.style.display = 'none';
})

connectCloseBtn.addEventListener("click", function() {
    connectFullEl.style.display = 'none';
    wireFullEll.style.display = 'none';
    proFullEl.style.display = 'none';
    OpticalfullEl.style.display = 'none';
    ITCOMfullEl.style.display = 'none';
})

Optical.addEventListener("click", function() {
    OpticalfullEl.style.display = 'block';
    proFullEl.style.display = 'none';
    connectFullEl.style.display = 'none';
    wireFullEll.style.display = 'none';
    ITCOMfullEl.style.display = 'none';
}) 

OpticalCloseBtn.addEventListener("click", function() {
    OpticalfullEl.style.display = 'none';
    connectFullEl.style.display = 'none';
    wireFullEll.style.display = 'none';
    proFullEl.style.display = 'none';
    ITCOMfullEl.style.display = 'none';
})

ITCOM.addEventListener("click", function() {
    ITCOMfullEl.style.display = 'block';
    proFullEl.style.display = 'none';
    wireFullEll.style.display = 'none';
    OpticalfullEl.style.display = 'none';
    connectFullEl.style.display = 'none';
}) 

ITCOMCloseBtn.addEventListener("click", function() {
    ITCOMfullEl.style.display = 'none';
    connectFullEl.style.display = 'none';
    wireFullEll.style.display = 'none';
    proFullEl.style.display = 'none';
})

// Solution element clickable //

const ITEl = document.getElementById('IT-El');
const ITELfullEl = document.querySelector('.IT-full-El');
let ITElCloseBtn = document.getElementById('IT-El-close-btn');
const Data = document.getElementById('Data');
const DatafullEl = document.querySelector('.Data-full-El');
let DataCloseBtn = document.getElementById('Data-close-btn');
const EnSecurity = document.getElementById('En-security');
const EnfullEl = document.querySelector('.En-full-El');
let EnCloseBtn = document.getElementById('En-close-btn');
const EnStorage = document.getElementById('En-storage');
const EnStofullEl = document.querySelector('.En-sto-full-El');
let EnStoCloseBtn = document.getElementById('En-sto-close-btn');
const EnSoftware = document.getElementById('En-software');
const EnSoftfullEl = document.querySelector('.En-soft-full-El');
let EnSoftCloseBtn = document.getElementById('En-soft-close-btn');




ITEl.addEventListener("click", function() {
    ITELfullEl.style.display = 'block';
    DatafullEl.style.display = 'none';
    EnfullEl.style.display = 'none';
    EnStofullEl.style.display = 'none';
    EnSoftfullEl.style.display = 'none';
});

ITElCloseBtn.addEventListener("click", function() {
    ITELfullEl.style.display = 'none';
    DatafullEl.style.display = 'none';
    EnfullEl.style.display = 'none';
    EnStofullEl.style.display = 'none';
    EnSoftfullEl.style.display = 'none';
});

Data.addEventListener("click", function() {
    DatafullEl.style.display = 'block';
    ITELfullEl.style.display = 'none';
    EnfullEl.style.display = 'none';
    EnStofullEl.style.display = 'none';
    EnSoftfullEl.style.display = 'none';
});

DataCloseBtn.addEventListener("click", function() {
    DatafullEl.style.display = 'none';
    ITELfullEl.style.display = 'none';
    EnfullEl.style.display = 'none';
    EnStofullEl.style.display = 'none';
    EnSoftfullEl.style.display = 'none';
});

EnSecurity.addEventListener("click", function() {
    EnfullEl.style.display = 'block';
    DatafullEl.style.display = 'none';
    ITELfullEl.style.display = 'none';
    EnStofullEl.style.display = 'none';
    EnSoftfullEl.style.display = 'none';
});

EnCloseBtn.addEventListener("click", function() {
    EnfullEl.style.display = 'none';
    DatafullEl.style.display = 'none';
    ITELfullEl.style.display = 'none';
    EnStofullEl.style.display = 'none';
    EnSoftfullEl.style.display = 'none';
});

EnStorage.addEventListener("click", function() {
    EnStofullEl.style.display = 'block';
    EnfullEl.style.display = 'none';
    EnSoftfullEl.style.display = 'none';
    DatafullEl.style.display = 'none';
    ITELfullEl.style.display = 'none';
});

EnStoCloseBtn.addEventListener("click", function() {
    EnStofullEl.style.display = 'none';
    EnfullEl.style.display = 'none';
    EnSoftfullEl.style.display = 'none';
    DatafullEl.style.display = 'none';
    ITELfullEl.style.display = 'none';
});

EnSoftware.addEventListener("click", function() {
    EnSoftfullEl.style.display = 'block';
    EnStofullEl.style.display = 'none';
    EnfullEl.style.display = 'none';
    DatafullEl.style.display = 'none';
    ITELfullEl.style.display = 'none';
});

EnSoftCloseBtn.addEventListener("click", function() {
    EnSoftfullEl.style.display = 'none';
    EnStofullEl.style.display = 'none';
    EnfullEl.style.display = 'none';
    DatafullEl.style.display = 'none';
    ITELfullEl.style.display = 'none';
});

// Support and Services element clickable //

const Document = document.getElementById('Document-El');
const DocumentfullEl = document.querySelector('.Document-full-El');
let DocumentCloseBtn = document.getElementById('Document-close-btn');
const Choose = document.getElementById('Choose');
const ChoosefullEl = document.querySelector('.Choose-full-El');
let ChooseCloseBtn = document.getElementById('Choose-close-btn');
const Professional = document.getElementById('Professional');
const ProfessionalfullEl = document.querySelector('.Professional-full-El');
let ProfessionalCloseBtn = document.getElementById('Professional-close-btn');
const Education = document.getElementById('Education');
const EducationfullEl = document.querySelector('.Education-full-El');
let EducationCloseBtn = document.getElementById('Education-close-btn');
const Symantec = document.getElementById('Symantec');
const SymantecfullEl = document.querySelector('.Symantec-full-El');
let SymantecCloseBtn = document.getElementById('Symantec-close-btn');
const Software = document.getElementById('Software');
const SoftwarefullEl = document.querySelector('.Software-full-El');
let SoftwareCloseBtn = document.getElementById('Software-close-btn');


Document.addEventListener("click", function() {
    DocumentfullEl.style.display = 'block';
    ChoosefullEl.style.display = 'none';
    ProfessionalfullEl.style.display = 'none';
    EducationfullEl.style.display = 'none';
    SymantecfullEl.style.display = 'none';
    SoftwarefullEl.style.display = 'none';
});

DocumentCloseBtn.addEventListener("click", function() {
    DocumentfullEl.style.display = 'none';
    ChoosefullEl.style.display = 'none';
    ProfessionalfullEl.style.display = 'none';
    EducationfullEl.style.display = 'none';
    SymantecfullEl.style.display = 'none';
    SoftwarefullEl.style.display = 'none';
});

Choose.addEventListener("click", function() {
    ChoosefullEl.style.display = 'block';
    DocumentfullEl.style.display = 'none';
    ProfessionalfullEl.style.display = 'none';
    EducationfullEl.style.display = 'none';
    SymantecfullEl.style.display = 'none';
    SoftwarefullEl.style.display = 'none';
});

ChooseCloseBtn.addEventListener("click", function() {
    ChoosefullEl.style.display = 'none';
    DocumentfullEl.style.display = 'none';
    ProfessionalfullEl.style.display = 'none';
    EducationfullEl.style.display = 'none';
    SymantecfullEl.style.display = 'none';
    SoftwarefullEl.style.display = 'none';
});

Professional.addEventListener("click", function() {
    ProfessionalfullEl.style.display = 'block';
    ChoosefullEl.style.display = 'none';
    DocumentfullEl.style.display = 'none';
    EducationfullEl.style.display = 'none';
    SymantecfullEl.style.display = 'none';
    SoftwarefullEl.style.display = 'none';
});

ProfessionalCloseBtn.addEventListener("click", function() {
    ProfessionalfullEl.style.display = 'none';
    ChoosefullEl.style.display = 'none';
    DocumentfullEl.style.display = 'none';
    EducationfullEl.style.display = 'none';
    SymantecfullEl.style.display = 'none';
    SoftwarefullEl.style.display = 'none';
});

Education.addEventListener("click", function() {
    EducationfullEl.style.display = 'block';
    ProfessionalfullEl.style.display = 'none';
    ChoosefullEl.style.display = 'none';
    DocumentfullEl.style.display = 'none';
    SymantecfullEl.style.display = 'none';
    SoftwarefullEl.style.display = 'none';
});

EducationCloseBtn.addEventListener("click", function() {
    EducationfullEl.style.display = 'none';
    ProfessionalfullEl.style.display = 'none';
    ChoosefullEl.style.display = 'none';
    DocumentfullEl.style.display = 'none';
    SymantecfullEl.style.display = 'none';
    SoftwarefullEl.style.display = 'none';
});

Symantec.addEventListener("click", function() {
    SymantecfullEl.style.display = 'block';
    EducationfullEl.style.display = 'none';
    ProfessionalfullEl.style.display = 'none';
    ChoosefullEl.style.display = 'none';
    DocumentfullEl.style.display = 'none';
    SoftwarefullEl.style.display = 'none';
});

SymantecCloseBtn.addEventListener("click", function() {
    SymantecfullEl.style.display = 'none';
    EducationfullEl.style.display = 'none';
    ProfessionalfullEl.style.display = 'none';
    ChoosefullEl.style.display = 'none';
    DocumentfullEl.style.display = 'none';
    SoftwarefullEl.style.display = 'none';
});

Software.addEventListener("click", function() {
    SoftwarefullEl.style.display = 'block';
    SymantecfullEl.style.display = 'none';
    EducationfullEl.style.display = 'none';
    ProfessionalfullEl.style.display = 'none';
    ChoosefullEl.style.display = 'none';
    DocumentfullEl.style.display = 'none';
});

SoftwareCloseBtn.addEventListener("click", function() {
    SoftwarefullEl.style.display = 'none';
    SymantecfullEl.style.display = 'none';
    EducationfullEl.style.display = 'none';
    ProfessionalfullEl.style.display = 'none';
    ChoosefullEl.style.display = 'none';
    DocumentfullEl.style.display = 'none';
});

// Company element clickable //

const About = document.getElementById('About');
const AboutfullEl = document.querySelector('.About-full-El');
let AboutCloseBtn = document.getElementById('About-close-btn');
const Blog = document.getElementById('Blog');
const BlogfullEl = document.querySelector('.Blog-full-El');
let BlogCloseBtn = document.getElementById('Blog-close-btn');
const Contact = document.getElementById('Contact');
const ContactfullEl = document.querySelector('.Contact-full-El');
let ContactCloseBtn = document.getElementById('Contact-close-btn');


About.addEventListener("click", function() {
    AboutfullEl.style.display = 'block';
    BlogfullEl.style.display = 'none';
    ContactfullEl.style.display = 'none';
});

AboutCloseBtn.addEventListener("click", function() {
    AboutfullEl.style.display = 'none';
    BlogfullEl.style.display = 'none';
    ContactfullEl.style.display = 'none';
});

Blog.addEventListener("click", function() {
    BlogfullEl.style.display = 'block';
    AboutfullEl.style.display = 'none';
    ContactfullEl.style.display = 'none';
});

BlogCloseBtn.addEventListener("click", function() {
    BlogfullEl.style.display = 'none';
    AboutfullEl.style.display = 'none';
    ContactfullEl.style.display = 'none';
});

Contact.addEventListener("click", function() {
    ContactfullEl.style.display = 'block';
    BlogfullEl.style.display = 'none';
    AboutfullEl.style.display = 'none';
});

ContactCloseBtn.addEventListener("click", function() {
    ContactfullEl.style.display = 'none';
    BlogfullEl.style.display = 'none';
    AboutfullEl.style.display = 'none';
});


// How-to-buy elements clickable //

const Hardware = document.getElementById('Hardware');
const HardwarefullEl = document.querySelector('.Hardware-full-El');
let HardwareCloseBtn = document.getElementById('Hardware-close-btn');

Hardware.addEventListener("click", function() {
    HardwarefullEl.style.display = 'block';
});    

HardwareCloseBtn.addEventListener("click", function() {
    HardwarefullEl.style.display = 'none';
}); 


//  Media Queries Menu bar // 

const menuIcon = document.querySelector('.menu-icon');
const listItems = document.querySelector('.list-items');
const portalMedia = document.querySelector('.portal');
const menuCancelBtn = document.querySelector('.menu-cancel-btn');

menuIcon.addEventListener('click', function() {
    menuIcon.style.display = 'none';
    listItems.style.display = 'flex';
    portalMedia.style.display = 'flex';
    menuCancelBtn.style.display = 'block';
});

menuCancelBtn.addEventListener('click', function() {
    menuIcon.style.display = 'flex';
    listItems.style.display = 'none';
    portalMedia.style.display = 'none';
    menuCancelBtn.style.display = 'none';


    proContainer.style.display = 'none';
    solContainer.style.display = 'none';
    supportContainer.style.display = 'none';
    companyContainer.style.display = 'none';
    howContainer.style.display = 'none';

    proFullEl.style.display = 'none'; // All 4 here are product full element products //
    wireFullEll.style.display = 'none';
    connectFullEl.style.display = 'none';
    OpticalfullEl.style.display = 'none';
    ITCOMfullEl.style.display = 'none';

    ITELfullEl.style.display = 'none'; // All 5 here are solution full element products //
    DatafullEl.style.display = 'none';
    EnfullEl.style.display = 'none';
    EnStofullEl.style.display = 'none';
    EnSoftfullEl.style.display = 'none';

    ChoosefullEl.style.display = 'none'; // All 6 here are Support and Servies element product //
    DocumentfullEl.style.display = 'none';
    ProfessionalfullEl.style.display = 'none';
    EducationfullEl.style.display = 'none';
    SymantecfullEl.style.display = 'none';
    SoftwarefullEl.style.display = 'none';

    AboutfullEl.style.display = 'none';  // All 3 here are Company elements products //
    BlogfullEl.style.display = 'none';
    ContactfullEl.style.display = 'none';

    HardwarefullEl.style.display = 'none'; // How-to-buy elements products //
});


