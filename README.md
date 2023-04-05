# FinalProject

### ความเป็นมาของโปรแกรม
=เนื่องจากการบันทึกข้อมูล และการเก็บข้อมูลไม่เป็นสัดส่วน ทำให้บางครั้งสินค้าตกหล่น เลยคิดโปรแกรมนี้ขึ้นมาเพื่อตอบสนองของผู้ใช้ที่เป็นพ่อค้าเเม่ค้าออนไลน์ เพื่อให้การเช็คออร์เดอร์ง่ายขึ้น


### วัตถุประสงค์ของโปรแกรม
=บันทึกข้อมูลของสินค้า


### โครงสร้างของโปรแกรม (Class diagram)

```mermaid
classDiagram
    Program <|-- DAEShop
    DAEShop <|-- TheChains
    DAEShop <|-- DeeperdarkPartyMonstarSleeveles
    DAEShop <|-- DeeperdarkTurtleStraws
    DAEShop <|-- LifeSucks
    DAEShop <|-- CuttingFarmHoodies
    DAEShop <|-- DeeperdarkSharkFinning
    DAEShop <|-- DeeperdarkKidnappedAMermaid
    DAEShop <|-- TheChainsSweater
    Program : +Main()
    class DAEShop{
        +openToolStripMenuItem_Click()
        +saveToolStripMenuItem_Click()
        +button2_Click()
    }
    class TheChains{
        +getName()
        +getColor()
        +getPrice()
        
    }
    class DeeperdarkPartyMonstarSleeveles{
        +getName()
        +getColor()
        +getPrice()
    }
    class DeeperdarkTurtleStraws{
        +getName()
        +getColor()
        +getPrice()    
    }
    class LifeSucks{
        +getName()
        +getColor()
        +getPrice()
    }
    class CuttingFarmHoodies{
        +getName()
        +getColor()
        +getPrice()
    }
    class DeeperdarkSharkFinning{
        +getName()
        +getColor()
        +getPrice()
    }
    class DeeperdarkKidnappedAMermaid{
        +getName()
        +getColor()
        +getPrice()
    }
    class TheChainsSweater{
        +getName()
        +getColor()
        +getPrice()
    }
```

### ชื่อของผู้พัฒนาโปรแกรม
653450089-1 ณัฐวรรณ พวงมะลัย
