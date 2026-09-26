# 7. Bottlenecks and Solutions

## 7.1 Stale Cache
**Problem:** Users may receive old content after a website update.  
**Solution:** Configure suitable cache duration and purge the cache when important content changes.

## 7.2 Custom Domain Configuration
**Problem:** DNS and certificate configuration may involve several steps.  
**Solution:** Carefully configure DNS records and use Azure-supported certificate management.

## 7.3 WAF False Positives
**Problem:** WAF may sometimes block legitimate requests.  
**Solution:** Analyze WAF logs and tune security rules carefully.

## 7.4 Incorrect Caching
**Problem:** Sensitive or personalized information could be incorrectly cached.  
**Solution:** Disable caching for authentication, personalized content, and sensitive API responses.
