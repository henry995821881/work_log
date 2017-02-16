select * from tab_goods_delivery_detail de --where de.carry_no='TD17020700008' 
order by de.create_time desc  --提单表 discussed 2156  csg_id 1171

-- 原来的理计交货单 select * from tab_goods_dvr_detail_p a where a.dvr_id=1171   

select * from tab_goods_csg_detail_p b where b.csg_id=1175 --磅计交货单

select * from tab_goods_deal deal where deal.buyorsell=1  order by deal.order_time desc  --订单表

--------------行列拼接 语法

select listagg((select 

discussid
--tstc_no
                 from tab_goods_deal
                where discussid = t1.att32
                 and buyorsell = 1),
              ',') within group(order by null) as deal_no_array
            
  from tab_order_s_p_detail_diss t1, tab_order_s_p_detail_diss t2
 where t1.att32 = t2.discussid
   and t1.att33 = t2.seq_d   
   and t1.domain_no = 2300
   and t1.discussid = 2173
----------------------------
--状态表
select * from TABF_DISOBEY_STAT st where st.busi_type =7


select de1.discussid from tab_goods_deal de1 where de1.tstc_no ='DD17020800001' and de1.buyorsell=1

select * from tab_order_s_p_detail_diss diss order by diss.seq_d desc

select p.discussid,p.discussid from tab_goods_csg_detail_p p


---合同表
select * from tab_subs_goods_detail subs where subs.buyorsell=1 and subs.subs_no='HT17020900001' order by subs.create_date desc



---洽谈明细表
select ss.att32 from tab_order_s_p_detail_diss ss where ss.discussid =2156


----20170215

select de.busi_type ,de.create_time from tab_goods_delivery_detail de order by de.create_time desc


select * from tab_goods_csg_detail_p p
order by csg_id desc

select * from tab_goods_delivery_detail where carry_id =474
 
select * from tab_subs_goods_detail where subs_id=2369--order by subs_id desc
select * from tab_goods_deal de1 where de1.status <>99 and de1.buyorsell=1 -- de.tstc_no='DD17021500002'
order by de1.deal_time desc

select * from tab_goods_csg_detail_p where subs_id=2369

select * from tab_goods_deal de2 where de2.discussid in
(select att32 from tab_order_s_p_detail_diss di1 where di1.discussid=2369)

select * from tab_subs_goods_detail where discussed =2369


select * from tab_order_s_p_detail_diss di2 where di2.discussid=2369
select * from tab_order_s_p_detail_diss di2 where di2.discussid=2368
select * from tab_goods_discuss_detail ll where ll.discussid =2369




 
