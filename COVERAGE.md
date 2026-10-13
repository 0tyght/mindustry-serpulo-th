# ขอบเขตของ Serpulo ไทย 2.0

ความครบของรุ่นนี้วัดจากงานการเล่น Serpulo ในตาราง ไม่ใช่จำนวนไฟล์มากกว่าชุดอื่น ทุกแบบใช้บล็อกเดิม มีชื่อ/คำอธิบายไทย และตรวจโครงสร้างด้วย Build 160.5 และ 160.7

## งานที่มีแบบรองรับ

| งาน | แบบในชุด | เงื่อนไขหลัก |
|---|---|---|
| 01 เริ่มฐานและ Core | 4 แบบ: [CORE-START-COAL](docs/schemes/CORE-START-COAL.md), [CORE101](docs/schemes/CORE101.md), [CORE102](docs/schemes/CORE102.md), [CORE201](docs/schemes/CORE201.md) | เลือกขนาด Core และเทคที่ปลดล็อกตามคู่มือ |
| 02 เหมืองและปั๊ม | 11 แบบ: [MINE101](docs/schemes/MINE101.md), [MINE102](docs/schemes/MINE102.md), [MINE103](docs/schemes/MINE103.md), [MINE104](docs/schemes/MINE104.md), [MINE105](docs/schemes/MINE105.md), [MINE106](docs/schemes/MINE106.md), [MINE201](docs/schemes/MINE201.md), [MINE202](docs/schemes/MINE202.md) และอีก 3 แบบ | รูปร่างแร่/น้ำจริงมีผล วางหัวขุด/ปั๊มตามเงื่อนไข |
| 03 โรงงาน | 61 แบบ: [PROD-001](docs/schemes/PROD-001.md), [PROD-002](docs/schemes/PROD-002.md), [PROD-003](docs/schemes/PROD-003.md), [PROD-004](docs/schemes/PROD-004.md), [PROD-005](docs/schemes/PROD-005.md), [PROD-006](docs/schemes/PROD-006.md), [PROD-007](docs/schemes/PROD-007.md), [PROD-008](docs/schemes/PROD-008.md) และอีก 53 แบบ | วัตถุดิบและทางออกต้องจ่าย/ระบายได้พอ |
| 04 ไฟฟ้า | 18 แบบ: [POWER101](docs/schemes/POWER101.md), [POWER102](docs/schemes/POWER102.md), [POWER103](docs/schemes/POWER103.md), [POWER104](docs/schemes/POWER104.md), [POWER105](docs/schemes/POWER105.md), [POWER106](docs/schemes/POWER106.md), [POWER107](docs/schemes/POWER107.md), [POWER108](docs/schemes/POWER108.md) และอีก 10 แบบ | เชื้อเพลิง หล่อเย็น และไฟเริ่มต้นตามแบบ |
| 05 ขนส่งและคลัง | 9 แบบ: [LOG101](docs/schemes/LOG101.md), [LOG102](docs/schemes/LOG102.md), [LOG103](docs/schemes/LOG103.md), [LOG104](docs/schemes/LOG104.md), [LOG105](docs/schemes/LOG105.md), [LOG201](docs/schemes/LOG201.md), [LOG202](docs/schemes/LOG202.md), [LOG203](docs/schemes/LOG203.md) และอีก 1 แบบ | ตั้งปลายทาง Mass Driver และแนบ Core ตามจุดที่ระบุ |
| 06 ป้องกัน | 17 แบบ: [DEF101](docs/schemes/DEF101.md), [DEF102](docs/schemes/DEF102.md), [DEF103](docs/schemes/DEF103.md), [DEF104](docs/schemes/DEF104.md), [DEF105](docs/schemes/DEF105.md), [DEF106](docs/schemes/DEF106.md), [DEF107](docs/schemes/DEF107.md), [DEF108](docs/schemes/DEF108.md) และอีก 9 แบบ | ด้านแนวรบ เป้าหมาย กระสุน ซ่อม/หล่อเย็น และโควตายูนิตของแบบไร้สาย |
| 07 ยูนิต | 52 แบบ: [SUPPORT201](docs/schemes/SUPPORT201.md), [SUPPORT202](docs/schemes/SUPPORT202.md), [SUPPORT203](docs/schemes/SUPPORT203.md), [SUPPORT204](docs/schemes/SUPPORT204.md), [SUPPORT205](docs/schemes/SUPPORT205.md), [SUPPORT206](docs/schemes/SUPPORT206.md), [SUPPORT207](docs/schemes/SUPPORT207.md), [SUPPORT208](docs/schemes/SUPPORT208.md) และอีก 44 แบบ | Core/โควตา ทางออกและไครโอของ T4/T5 |
| 08 ส่งรับ v8 | 65 แบบ: [CARGO-BELT-blast-compound](docs/schemes/CARGO-BELT-blast-compound.md), [CARGO-BELT-coal](docs/schemes/CARGO-BELT-coal.md), [CARGO-BELT-copper](docs/schemes/CARGO-BELT-copper.md), [CARGO-BELT-graphite](docs/schemes/CARGO-BELT-graphite.md), [CARGO-BELT-lead](docs/schemes/CARGO-BELT-lead.md), [CARGO-BELT-metaglass](docs/schemes/CARGO-BELT-metaglass.md), [CARGO-BELT-phase-fabric](docs/schemes/CARGO-BELT-phase-fabric.md), [CARGO-BELT-plastanium](docs/schemes/CARGO-BELT-plastanium.md) และอีก 57 แบบ | แคมเปญระบบใหม่ โฮสต์กำหนดเส้นทาง น้ำมันต้นทางและน้ำปลายทาง |
| 09 สนับสนุนและ Logic | 9 แบบ: [SUPPORT101](docs/schemes/SUPPORT101.md), [SUPPORT102](docs/schemes/SUPPORT102.md), [SUPPORT103](docs/schemes/SUPPORT103.md), [SUPPORT104](docs/schemes/SUPPORT104.md), [SUPPORT105](docs/schemes/SUPPORT105.md), [SUPPORT106](docs/schemes/SUPPORT106.md), [SUPPORT303](docs/schemes/SUPPORT303.md), [SUPPORT305](docs/schemes/SUPPORT305.md) และอีก 1 แบบ | ลิงก์และยูนิตที่ logic ต้องใช้ตามคู่มือ |

## วัตถุดิบและโรงงาน

| กลุ่ม | ตัวเลือก |
|---|---|
| blast-compound | [PROD-030](docs/schemes/PROD-030.md), [PROD-031](docs/schemes/PROD-031.md), [PROD-032](docs/schemes/PROD-032.md) |
| coal | [PROD-043](docs/schemes/PROD-043.md), [PROD-044](docs/schemes/PROD-044.md), [PROD-045](docs/schemes/PROD-045.md) |
| cryofluid | [PROD-055](docs/schemes/PROD-055.md), [PROD-056](docs/schemes/PROD-056.md), [PROD-057](docs/schemes/PROD-057.md), [PROD-058](docs/schemes/PROD-058.md) |
| cultivator | [PROD-046](docs/schemes/PROD-046.md), [PROD-047](docs/schemes/PROD-047.md), [PROD-048](docs/schemes/PROD-048.md) |
| graphite | [PROD-001](docs/schemes/PROD-001.md), [PROD-002](docs/schemes/PROD-002.md), [PROD-003](docs/schemes/PROD-003.md), [PROD-004](docs/schemes/PROD-004.md) |
| graphite-multipress | [PROD-005](docs/schemes/PROD-005.md), [PROD-006](docs/schemes/PROD-006.md), [PROD-007](docs/schemes/PROD-007.md) |
| melter | [PROD-036](docs/schemes/PROD-036.md), [PROD-037](docs/schemes/PROD-037.md) |
| metaglass | [PROD-015](docs/schemes/PROD-015.md), [PROD-016](docs/schemes/PROD-016.md), [PROD-017](docs/schemes/PROD-017.md), [PROD-061](docs/schemes/PROD-061.md) |
| oil-extractor | [PROD-052](docs/schemes/PROD-052.md), [PROD-053](docs/schemes/PROD-053.md), [PROD-054](docs/schemes/PROD-054.md) |
| phase-fabric | [PROD-021](docs/schemes/PROD-021.md), [PROD-022](docs/schemes/PROD-022.md), [PROD-023](docs/schemes/PROD-023.md) |
| plastanium | [PROD-018](docs/schemes/PROD-018.md), [PROD-019](docs/schemes/PROD-019.md), [PROD-020](docs/schemes/PROD-020.md) |
| pulveriser | [PROD-033](docs/schemes/PROD-033.md), [PROD-034](docs/schemes/PROD-034.md), [PROD-035](docs/schemes/PROD-035.md) |
| pyratite | [PROD-027](docs/schemes/PROD-027.md), [PROD-028](docs/schemes/PROD-028.md), [PROD-029](docs/schemes/PROD-029.md) |
| scrap | [PROD-041](docs/schemes/PROD-041.md), [PROD-042](docs/schemes/PROD-042.md) |
| separator | [PROD-038](docs/schemes/PROD-038.md), [PROD-039](docs/schemes/PROD-039.md), [PROD-040](docs/schemes/PROD-040.md) |
| silicon | [PROD-008](docs/schemes/PROD-008.md), [PROD-009](docs/schemes/PROD-009.md), [PROD-010](docs/schemes/PROD-010.md), [PROD-011](docs/schemes/PROD-011.md), [PROD-059](docs/schemes/PROD-059.md), [PROD-060](docs/schemes/PROD-060.md) |
| silicon-crucible | [PROD-012](docs/schemes/PROD-012.md), [PROD-013](docs/schemes/PROD-013.md), [PROD-014](docs/schemes/PROD-014.md) |
| spore-press | [PROD-049](docs/schemes/PROD-049.md), [PROD-050](docs/schemes/PROD-050.md), [PROD-051](docs/schemes/PROD-051.md) |
| surge-alloy | [PROD-024](docs/schemes/PROD-024.md), [PROD-025](docs/schemes/PROD-025.md), [PROD-026](docs/schemes/PROD-026.md) |

## ยูนิตครบทั้งเจ็ดสาย

แบบหลักแต่ละสายมี T1–T5 ให้เลือก โดยรุ่น T2 ขึ้นไปมีโรงงานเริ่มต้นและเครื่องอัปเกรดต่อ payload ไว้ครบ และมีผังคัดเพิ่มเติมที่รวมการผลิตไครโอ น้ำ และการป้อนจาก Core

| สาย | T1 | T2 | T3 | T4 | T5 |
|---|---|---|---|---|---|
| เดินยิง | [T1](docs/schemes/UNIT-DAGGER-T1.md) | [T2](docs/schemes/UNIT-DAGGER-T2.md) | [T3](docs/schemes/UNIT-DAGGER-T3.md) | [T4](docs/schemes/UNIT-DAGGER-T4.md) | [T5](docs/schemes/UNIT-DAGGER-T5.md) |
| แมงมุม | [T1](docs/schemes/UNIT-CRAWLER-T1.md) | [T2](docs/schemes/UNIT-CRAWLER-T2.md) | [T3](docs/schemes/UNIT-CRAWLER-T3.md) | [T4](docs/schemes/UNIT-CRAWLER-T4.md) | [T5](docs/schemes/UNIT-CRAWLER-T5.md) |
| สนับสนุนภาคพื้น | [T1](docs/schemes/UNIT-NOVA-T1.md) | [T2](docs/schemes/UNIT-NOVA-T2.md) | [T3](docs/schemes/UNIT-NOVA-T3.md) | [T4](docs/schemes/UNIT-NOVA-T4.md) | [T5](docs/schemes/UNIT-NOVA-T5.md) |
| บินโจมตี | [T1](docs/schemes/UNIT-FLARE-T1.md) | [T2](docs/schemes/UNIT-FLARE-T2.md) | [T3](docs/schemes/UNIT-FLARE-T3.md) | [T4](docs/schemes/UNIT-FLARE-T4.md) | [T5](docs/schemes/UNIT-FLARE-T5.md) |
| บินช่วยฐาน | [T1](docs/schemes/UNIT-MONO-T1.md) | [T2](docs/schemes/UNIT-MONO-T2.md) | [T3](docs/schemes/UNIT-MONO-T3.md) | [T4](docs/schemes/UNIT-MONO-T4.md) | [T5](docs/schemes/UNIT-MONO-T5.md) |
| เรือโจมตี | [T1](docs/schemes/UNIT-RISSO-T1.md) | [T2](docs/schemes/UNIT-RISSO-T2.md) | [T3](docs/schemes/UNIT-RISSO-T3.md) | [T4](docs/schemes/UNIT-RISSO-T4.md) | [T5](docs/schemes/UNIT-RISSO-T5.md) |
| เรือสนับสนุน | [T1](docs/schemes/UNIT-RETUSA-T1.md) | [T2](docs/schemes/UNIT-RETUSA-T2.md) | [T3](docs/schemes/UNIT-RETUSA-T3.md) | [T4](docs/schemes/UNIT-RETUSA-T4.md) | [T5](docs/schemes/UNIT-RETUSA-T5.md) |

## ส่งรับ v8

ครบทรัพยากร 16 ชนิด มีสี่บทบาทต่อชนิด: รับจากสายผลิตเพื่อส่ง, ดึงจากคลังแนบ Core เพื่อส่ง, รับพร้อมขุดน้ำเองระดับ 200/นาที และรับอัตราสูงพร้อมน้ำภายนอกประมาณ 1100/นาที

## เทียบมาตรฐานกับ CMD

| ประเด็น | CMD ที่ตรวจ | รุ่น 2.0 นี้ |
|---|---|---|
| ผังหลายเครื่องร่วมระบบ | มีโรงงาน ไฟ ป้องกันและยูนิตรวมระบบ | คัดผังลักษณะนี้จากแหล่ง MIT และเพิ่มบทบาทที่ขาด แทนชุดเครื่องเดี่ยวรุ่นแรก |
| ยูนิต | มีตัวเลือก T5 แต่ต้องเลือกผัง/เงื่อนไขเอง | ตารางเจ็ดสายครบ T1–T5 และทดสอบการปล่อยยูนิตปลายทางทั้ง 35 แบบ |
| ส่งรับหลังอัปเดต | ไม่มี Advanced Launch Pad / Landing Pad ในชุดที่ตรวจ | น้ำมันจากสปอร์ ฐานรับขุดน้ำเองและอัตราสูง พร้อมแบบสินค้าครบ16ชนิด |
| ภาษาและวิธีใช้ | ชื่อส่วนใหญ่รัสเซีย หลายแบบไม่มีคำอธิบาย | ชื่อไทย หมวด จุดต่อ วัสดุ เงื่อนไข ภาพบล็อกจริง และสถานะทดสอบทุกแบบ |
| การตรวจ | ตรวจ CMD เพื่อเทียบรูปแบบ ไม่ได้วัดอัตราทุกไฟล์ | แยกการตรวจผังจากการจำลองระบบ รายงานอัตราที่วัดได้และข้อจำกัด |

รุ่นนี้ไม่อ้างว่าทุกผังเหนือกว่าทุกผังใน CMD หรือครอบคลุมกติกาเซิร์ฟเวอร์เฉพาะทุกแบบ งานศิลปะ/มินิเกม/แบบ sandbox ที่ต้องใช้ Source/Void และบล็อก Erekir ไม่อยู่ในชุด Serpulo สำหรับเล่นปกตินี้
