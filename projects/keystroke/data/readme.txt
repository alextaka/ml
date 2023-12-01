A 20-participant sample of the collected data that will be published with the paper (overall more than 168,000 participants)

The metadata_participants.txt contains demographics and derived metrics for each participant.
The column names are described as follows:
PARTICIPANT_ID			Unique ID of participant
AGE						Participant's age
GENDER					Participant's gender
HAS_TAKEN_TYPING_COURSE	Whether the participant has taken a typing course (1) or not (0)
COUNTRY					Country from which the participant has taken the study
KEYBOARD_LAYOUT			QWERTY, AZERTY, QWERTZ or other layout
NATIVE_LANGUAGE			Native language of participant
FINGERS					choice between 1-2, 3-4, 5-6, 7-8 and 9-10 fingers used
TIME_SPENT_TYPING		Number of hours spent typing per day
KEYBOARD_TYPE			full (desktop), laptop, small (physical) or (on-screen) touch keyboard
ERROR_RATE(%)			Average error rate
AVG_WPM					Average words per minute
AVG_IKI					Average inter-key interval
ROLLOVER				Average rollover ratio
KSPC					Average Keystrokes per Character
AVG_KEYPRESS			Average keypress duration

Files named <number>_keystrokes.txt are the keystroke-by-keystroke logs for all test sentences transcribed by the participant ID = <number>.
The column names are described as follows: 
PARTICIPANT_ID			Unique ID of participant
TEST_SECTION_ID			Unique ID of sentence within a participant's test
SENTENCE				Presented sentence
USER_INPUT				Transcribed sentence
KEYSTROKE_ID			Unique keystroke id (across all participants)
PRESS_TIME				Timestamp when the key was pressed
RELEASE_TIME			Timestamp when the key was released
LETTER					String representation of the pressed key
KEYCODE					JavaScript keycode of the pressed key
For some users, the typed letter was not logged correctly. Instead, the corresponding javascript keycode can be used. 

