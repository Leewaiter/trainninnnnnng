# trainninnnnnng
test

iOS
strong, unowned, weak

strong 
當你確定需要長期持有某個物件,且該物件不應該在引用期間被銷毀
如果兩個物件互相強引用,可能導致 "循環引用" 造成記憶體洩漏

unowned
不可為nil,
一個物件在其生命週期內始終依賴另一個物件
如為nil則會崩潰

weak
必須為 var,因為可能變nil
運行時有少量開銷(追蹤 nil 狀態)
