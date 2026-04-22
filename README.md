# Thai WSD — "ตา" Disambiguation

A Word-sense Disambiguation (WSD) model for the Thai homonym **"ตา"**, 
which can carry multiple meanings depending on context.

## Classes
| Label | Meaning | Example |
|-------|---------|---------|
| E | Eye (อวัยวะ) | ดวงตา, จ้องตา |
| P | Person (บุคคล) | ตา = พ่อของแม่, เรียกผู้ชาย |
| T | Time/Turn (เวลา/คราว) | ตาใคร, ถึงตา |

## Input / Output
Input: Thai sentence string containing the word "ตา"
Output: Semantic class — E, P, or T

## Example
Input:
1. สัตว์ประหลาดตัวนั้นมีดวงตาหลายดวงมาก
2. ดูจากรูปหน้าและดวงตาของแกแล้วก็หล่อเหลา
3. ผมว่าผมชอบจ้องตาคุณมากเลยล่ะ
4. จ้องตากันแบบนี้ไม่กลัวยายจะว่าหรอคะ

Output: E, E, E, P
