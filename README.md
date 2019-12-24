# scte35-parser
SCTE 35 Parser in C
Digital Program Insertion Cueing Message for Cable.

SCTE 35, Digital Program Insertion Cueing Message for Cable, is the core signaling standard for advertising and distribution control (ex. blackouts) of content for content providers and content distributors. 
SCTE 35 is being applied to QAM/IP, Title VI/TVE (TV Everywhere), and live/time shifted (DVR, VOD, etc.) delivery. SCTE 35 signals can be used to identify advertising breaks, advertising content, and programming content 
(ex. specific Programs and Chapters within a Program).
SCTE 35 complements other Standards to complete the eco-systems. 
[SCTE 30] is used to support splicing of advertising into live QAM MPEG-2 transport streams. [SCTE 130-3] is used to support alternate content decisions 
(advertising, blackouts, stream switching) for live and time shifted delivery. 
[SCTE 214-1] defines how SCTE 35 is carried in MPEG-DASH. 
[SCTE 224] (ESNI) is used to pass event and policy information from provider or other systems to communicate distribution control instructions. 
[SCTE 172] defines additional video coding and transport constraints on ANSI/SCTE 128 (which constrains ITU-T H.264/ ISO/IEC 14496-10 (“AVC”)
video compression) for Digital Program Insertion applications using SCTE 35 messaging.

1.2.  Scope

This standard supports delivery of events, frame accurate or non-frame accurate, and associated descriptive data in MPEG-2 transport streams, MPEG-DASH and HLS. This standard supports the splicing of content (MPEG-2 transport streams, MPEG-DASH, etc.) for the purpose of Digital Program Insertion, which includes advertisement insertion and insertion of other content types. An in-stream messaging mechanism is defined to signal splicing and insertion opportunities and it is not intended to ensure seamless insertion (splicing, playlist, etc.). As such, this standard does not specify the insertion method used or constraints applied to the content being inserted, nor does it address constraints placed on insertion devices.




