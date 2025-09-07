# Ksenia's Ravelry Trends | Ravelry.api

[API Reference Guide](https://www.ravelry.com/api)  
[Tableau Public Dashboard](https://public.tableau.com/app/profile/ksenia.bukshtynova/viz/RavelryTrends/RavelryTrends)

### Future Enhancements:
- [x] Figure out how to pull additional pattern information to retrieve yarn weight, gauge, difficulty, etc **(complete on August 6<sup>th</sup>, 2025)**
- [x] Compile data, begin dashboard 
- [ ] Switch from Basic Auth to OAuth 2.0
- [ ] Implement incremental data pull:
	1.  Compare if favorite is already in the data store
	2.  If not present, retreive favorite information and pattern information and append
	3.  If present, skip, no updates requred