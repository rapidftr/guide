**Description:**
Fetches the latest set of form sections from the system.

**URL:**
http://localhost:3000/published_form_sections/

**Formats:**
JSON

**HTTP Method:**
GET

**Requires Authentication:**
true

**Parameters:**
none

**Returns:**
All form sections in json format

**Example:** http://localhost:3000/published_form_sections/
` [{"name":"Basic Identity","unique_id":"basic_identity","_rev":"1-01b61b52ac231f0f06166b6f8e0549e2","_id":"59cd40f39ab6aa791f73885e3bbd80fa","fields":[{"name":"name","enabled":true,"highlight_information":{"order":1,"highlighted":true},"editable":false,"type":"text_field","display_name":"Name"},{"name":"rc_id_no","enabled":true,"highlight_information":{"order":2,"highlighted":true},"editable":true,"type":"text_field","display_name":"RC ID No."},{"name":"protection_status","option_strings":["","Unaccompanied","Separated"],"help_text":"A separated child is any person under the age of 18, separated from both parents or from his/her previous legal or customary primary care giver, but not necessarily from other relatives. An unaccompanied child is any person who meets those criteria but is ALSO separated from his/her relatives.","enabled":true,"highlight_information":{"order":3,"highlighted":true},"editable":true,"type":"select_box","display_name":"Protection Status"},{"name":"id_document","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Personal ID Document No."},{"name":"gender","option_strings":["","Male","Female"],"enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"select_box","display_name":"Sex"},{"name":"nick_name","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Also Known As (nickname)"},{"name":"names_origin","option_strings":["","Yes","No"],"enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"select_box","display_name":"Name(s) given to child after separation?"},{"name":"dob_or_age","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Date of Birth / Age"},{"name":"birthplace","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Birthplace"},{"name":"nationality","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Nationality"},{"name":"ethnicity_or_tribe","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Ethnic group / tribe"},{"name":"languages","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Languages spoken"},{"name":"characteristics","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"textarea","display_name":"Distinguishing Physical Characteristics"},{"name":"documents","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Documents carried by the child"},{"name":"current_photo_key","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"photo_upload_box","display_name":"Current Photo Key"},{"name":"recorded_audio","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"audio_upload_box","display_name":"Recorded Audio"}],"enabled":true,"order":1,"editable":true,"couchrest-type":"FormSection","description":"Basic identity information about a separated or unaccompanied child.","perm_enabled":true},{"name":"Family details","unique_id":"family_details","_rev":"1-640b01189bffd50a6401edc068d7bf83","_id":"59cd40f39ab6aa791f73885e3bbd777a","fields":[{"name":"fathers_name","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Father's Name"},{"name":"is_father_alive","option_strings":["","Unknown","Alive","Dead"],"enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"select_box","display_name":"Is Father Alive?"},{"name":"father_death_details","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"If dead, please provide details"},{"name":"mothers_name","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Mother's Name"},{"name":"is_mother_alive","option_strings":["","Unknown","Alive","Dead"],"enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"select_box","display_name":"Is Mother Alive?"},{"name":"mother_death_details","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"If dead, please provide details"},{"name":"other_family","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"textarea","display_name":"Other persons well known to the child"},{"name":"address","help_text":"If the child does not remember his/her address, please note other relevant information, such as descriptions of mosques, churches, schools and other landmarks.","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"textarea","display_name":"Address of child before separation (and person with whom he/she lived)"},{"name":"telephone","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Telephone Before Separation"},{"name":"caregivers_name","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Caregiver's Name (if different)"},{"name":"is_caregiver_alive","option_strings":["Unknown","Alive","Dead"],"enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"select_box","display_name":"Is Caregiver Alive?"},{"name":"other_child_1","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"1) Sibling or other child accompanying the child"},{"name":"other_child_1_relationship","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Relationship"},{"name":"other_child_1_dob","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Date of Birth"},{"name":"other_child_1_birthplace","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Birthplace"},{"name":"other_child_1_address","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Current Address"},{"name":"other_child_1_telephone","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Telephone"},{"name":"other_child_2","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"2) Sibling or other child accompanying the child"},{"name":"other_child_2_relationship","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Relationship"},{"name":"other_child_2_dob","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Date of Birth"},{"name":"other_child_2_birthplace","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Birthplace"},{"name":"other_child_2_address","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Current Address"},{"name":"other_child_2_telephone","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Telephone"},{"name":"other_child_3","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"3) Sibling or other child accompanying the child"},{"name":"other_child_3_relationship","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Relationship"},{"name":"other_child_3_dob","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Date of Birth"},{"name":"other_child_3_birthplace","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Birthplace"},{"name":"other_child_3_address","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Current Address"},{"name":"other_child_3_telephone","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Telephone"}],"enabled":true,"order":2,"editable":true,"couchrest-type":"FormSection","description":"Information about a child's known family","perm_enabled":false},{"name":"Care Arrangements","unique_id":"care_arrangements","_rev":"1-4026571266874d9d92efccfb9740b26a","_id":"59cd40f39ab6aa791f73885e3bbd6b72","fields":[{"name":"care_arrangements","option_strings":["","Children's Center","Other Family Member(s)","Foster Family","Alone","Other"],"enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"select_box","display_name":"Current Care Arrangements"},{"name":"care_arrangements_other","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"If other, please provide details."},{"name":"care_arrangments_name","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Full Name"},{"name":"care_arrangements_relationship","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Relationship To Child"},{"name":"care_arrangements_knowsfamily","option_strings":["","Yes","No"],"enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"select_box","display_name":"Does the caregiver know the family of the child?"},{"name":"care_arrangements_familyinfo","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"textarea","display_name":"Caregiver's information about child or family"},{"name":"care_arrangements_address","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Child's current address (of caretaker or centre)"},{"name":"care_arrangements_came_from","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Child Arriving From"},{"name":"care_arrangements_arrival_date","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Arrival Date"}],"enabled":true,"order":3,"editable":true,"couchrest-type":"FormSection","description":"Information about the child's current caregiver","perm_enabled":false},{"name":"Separation History","unique_id":"separation_history","_rev":"1-f8aaca3b219f71a6ceb50cd28b636551","_id":"59cd40f39ab6aa791f73885e3bbd5bee","fields":[{"name":"separation_date","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Date of Separation"},{"name":"separation_place","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Place of Separation."},{"name":"separation_details","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"textarea","display_name":"Circumstances of Separation (please provide details)"},{"name":"evacuation_status","option_strings":["","Yes","No"],"enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"select_box","display_name":"Has child been evacuated?"},{"name":"evacuation_agent","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"If yes, through which organization?"},{"name":"evacuation_from","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Evacuated From"},{"name":"evacuation_to","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Evacuated To"},{"name":"evacuation_date","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Evacuation Date"},{"name":"care_arrangements_arrival_date","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Arrival Date"}],"enabled":true,"order":4,"editable":true,"couchrest-type":"FormSection","description":"The child's separation and evacuation history.","perm_enabled":false},{"name":"Protection Concerns","unique_id":"protection_concerns","_rev":"1-4689e86cc704eb6086d9ddc194777ae7","_id":"59cd40f39ab6aa791f73885e3bbd4f55","fields":[{"name":"concerns_chh","option_strings":["","Yes","No"],"enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"select_box","display_name":"Child Headed Household"},{"name":"concerns_disabled","option_strings":["","Yes","No"],"enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"select_box","display_name":"Disabled Child"},{"name":"concerns_medical_case","option_strings":["","Yes","No"],"enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"select_box","display_name":"Medical Case"},{"name":"concerns_street_child","option_strings":["","Yes","No"],"enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"select_box","display_name":"Street Child"},{"name":"concerns_girl_mother","option_strings":["","Yes","No"],"enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"select_box","display_name":"Girl Mother"},{"name":"concerns_vulnerable_person","option_strings":["","Yes","No"],"enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"select_box","display_name":"Living with Vulnerable Person"},{"name":"concerns_abuse_situation","option_strings":["","Yes","No"],"enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"select_box","display_name":"Girl Mother"},{"name":"concerns_other","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Other (please specify)"},{"name":"concerns_further_info","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"textarea","display_name":"Further Information"},{"name":"concerns_needs_followup","option_strings":["","Yes","No"],"enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"select_box","display_name":"Specific Follow-up Required?"},{"name":"concerns_followup_details","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"textarea","display_name":"Please specify follow-up needs."}],"enabled":true,"order":5,"editable":true,"couchrest-type":"FormSection","description":"","perm_enabled":false},{"name":"Childs Wishes","unique_id":"childs_wishes","_rev":"1-e606541be14e3366300f7fd3bd409b7f","_id":"59cd40f39ab6aa791f73885e3bbd4abf","fields":[{"name":"wishes_name_1","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Person child wishes to locate - Preferred"},{"name":"wishes_telephone_1","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Telephone"},{"name":"wishes_address_1","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"textarea","display_name":"Last Known Address"},{"name":"wishes_name_2","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Person child wishes to locate - Second Choice"},{"name":"wishes_telephone_2","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Telephone"},{"name":"wishes_address_2","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"textarea","display_name":"Last Known Address"},{"name":"wishes_name_3","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Person child wishes to locate - Third Choice"},{"name":"wishes_telephone_3","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Telephone"},{"name":"wishes_address_3","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"textarea","display_name":"Last Known Address"},{"name":"wishes_contacted","option_strings":["","Yes","No"],"enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"select_box","display_name":"Has the child heard from / been in contact with any relatives?"},{"name":"wishes_contacted_details","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"textarea","display_name":"Please give details"},{"name":"wishes_wants_contact","option_strings":["","Yes, as soon as possible","Yes, later","No"],"enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"select_box","display_name":"Does child want to be reunited with family?"},{"name":"wishes_contacted_details","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"textarea","display_name":"Please explain why"}],"enabled":true,"order":6,"editable":true,"couchrest-type":"FormSection","description":"","perm_enabled":false},{"name":"Other Interviews","unique_id":"other_interviews","_rev":"1-1bb46bdb3da8583bca4838e13b6c4647","_id":"59cd40f39ab6aa791f73885e3bbd3ec5","fields":[{"name":"other_org_interview_status","option_strings":["","Yes","No"],"enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"select_box","display_name":"Has the child been interviewed by another organization?"},{"name":"other_org_name","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Name of Organization"},{"name":"other_org_place","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Place of Interview"},{"name":"other_org_country","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Country"},{"name":"other_org_date","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Date"},{"name":"orther_org_reference_no","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Reference No. given to child by other organization"}],"enabled":true,"order":7,"editable":true,"couchrest-type":"FormSection","description":"","perm_enabled":false},{"name":"Other Tracing Info","unique_id":"other_tracing_info","_rev":"1-ae36c0e3fa1bc6db6684e630e302b483","_id":"59cd40f39ab6aa791f73885e3bbd3d09","fields":[{"name":"additional_tracing_info","help_text":"Such as key persons/location in the life of the child who/which might provide information about the location of the sought family -- e.g. names of religious leader, market place, etc. Please ask the child where he/she thinks relatives and siblings might be, and if the child is in contact with any family friends. Include any useful information the caregiver provides.","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"textarea","display_name":"Additional Info That Could Help In Tracing?"}],"enabled":true,"order":8,"editable":true,"couchrest-type":"FormSection","description":"","perm_enabled":false},{"name":"Interview Details","unique_id":"interview_details","_rev":"1-d0a1aa97fa7e5d5a6f6191fb691f8f45","_id":"59cd40f39ab6aa791f73885e3bbd2f39","fields":[{"name":"disclosure_public_name","option_strings":["","Yes","No"],"enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"select_box","display_name":"Does Child/Caregiver agree to share name on posters/radio/Internet?"},{"name":"disclosure_public_photo","option_strings":["","Yes","No"],"enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"select_box","display_name":"Photo?"},{"name":"disclosure_public_relatives","option_strings":["","Yes","No"],"enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"select_box","display_name":"Names of Relatives?"},{"name":"disclosure_other_orgs","option_strings":["","Yes","No"],"enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"select_box","display_name":"Does Child/Caregiver agree to share collected information with other organizations?"},{"name":"disclosure_authorities","option_strings":["","Yes","No"],"enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"select_box","display_name":"The authorities?"},{"name":"disclosure_deny_details","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"textarea","display_name":"If child does not agree, specify what cannot be shared and why."},{"name":"interview_place","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Place of Interview"},{"name":"interview_date","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Date"},{"name":"interview_subject","option_strings":["","the child","caregiver","other"],"enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"select_box","display_name":"Information Obtained From"},{"name":"interview_subject_details","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"If other, please specify"},{"name":"interviewer","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Name of Interviewer"},{"name":"interviewers_org","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Interviewer's Organization"},{"name":"governing_org","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Organization in charge of tracing child's family"}],"enabled":true,"order":9,"editable":true,"couchrest-type":"FormSection","description":"","perm_enabled":false},{"name":"Automation Form","unique_id":"b02512fe","_rev":"1-e912756d846bd60569d3e5a3e47b21de","_id":"59cd40f39ab6aa791f73885e3bbd211a","fields":[{"name":"b024ded8","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"text_field","display_name":"Automation TextField"},{"name":"b024e892","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"textarea","display_name":"Automation TextArea"},{"name":"b024efc2","option_strings":["Check 1","Check 2","Check 3"],"enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"check_boxes","display_name":"Automation CheckBoxes"},{"name":"b024f6a2","option_strings":["Select 1","Select 2","Select 3"],"enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"select_box","display_name":"Automation Select"},{"name":"b024fd82","option_strings":["Radio 1","Radio 2","Radio 3"],"enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"radio_button","display_name":"Automation Radio"},{"name":"b02503a4","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"numeric_field","display_name":"Automation Number"},{"name":"b02509bc","enabled":true,"highlight_information":{"highlighted":false},"editable":true,"type":"date_field","display_name":"Automation Date"}],"enabled":true,"order":10,"editable":true,"couchrest-type":"FormSection","description":"Automation Form","perm_enabled":false}]`

***

**Description:**
YET TO BE IMPLEMENTED. Fetch the latest form sections which are last updated at based on the date timestamp.

**URL:**
http://localhost:3000/published_form_sections?last_updated_at="2012-10-31:09:37:00"

**Formats:**
JSON

**HTTP Method:**
GET

**Requires Authentication:**
true

**Parameters:**
none

**Returns:**
All form sections in json format

**Example:** http://localhost:3000/published_form_sections?last_updated_at="2012-10-31:09:37:00"
> returns a 200 OK if the details on the client are same as on the server.
This helps us not to download the content once again from the server.