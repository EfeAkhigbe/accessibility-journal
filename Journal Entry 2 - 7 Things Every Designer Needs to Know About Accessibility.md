# Journal Entry 2: 7 Things Every Designer Needs to Know About Accessibility

---

Today, I read an article titled [7 Things Every Designer Needs to Know About Accessibility](https://medium.com/salesforce-ux/7-things-every-designer-needs-to-know-about-accessibility-64f105f0881b).

I learned a lot from this article, and I’ll be sharing all the key takeaways below.

---

### 1. Accessibility is not a barrier to innovation.  
This is absolutely true. Accessibility shouldn’t hinder innovation—instead, it should enhance and elevate it.  

When people think of accessibility, they often imagine designs that lack visual appeal—plain and basic. But that’s not true. Accessible designs can be beautiful, interactive, and enjoyable.  

Designing with accessibility in mind enhances the overall user experience. It benefits *all* users, not just a specific group.

---

### 2. Don’t use color as the only visual means of conveying information.  
Relying solely on color to convey messages is problematic, as not all users perceive color the same way.  

Whenever you use color to communicate something in your design, always include icons or explanatory text as well.  

The article highlights a powerful statistic to support this point:  
> 1 in 12 men, 1 in 200 women have color vision deficiency, 1 in 30 people have low vision, and 1 in 188 are blind. 

Here are some important nuggets for creating accessible forms:  
- Include icons to better convey messages (e.g., error or success messages).  
- Use text to explain why a field is in error.  
- Use tooltips, thick borders, bold text, underlines, or italics to make messages clearer.

---

### 3. Ensure sufficient contrast between text and background.  
I learned some things here that will significantly improve my design skills:  
- For **bold** text, the lightest grey you should use on a white background is `#959595`.  
- For **regular** text, the lightest grey is `#767676`.  
- Use **ColorSafe** to find accessible color palettes for your designs.  
- Placeholder or ghost text in form fields must follow **WCAG** guidelines. However, inactive buttons and items are exempt from this rule.

---

### 4. Provide a visible focus indicator for keyboard navigation.  
Always create your own styling for focus indicators instead of relying on the default browser style. The default may not be accessible or visually compatible with your design.  

Use a combination of the browser's default focus and a tooltip to show keyboard focus clearly.

---

### 5. Be careful with forms.  
**Forms should always have clear borders.** This helps users who rely on adaptive pointing devices to navigate.

**Always add labels to your form fields.** Placeholder text is *not* a replacement for labels—they serve different purposes. Labels explain the function of a field and are essential for screen reader users.

---

### 6. Avoid component identity crises.  
Keep components simple and intuitive. Assistive technologies may not always be able to interpret the identity, function, and state of overly complex or ambiguous components.

---

### 7. Don’t make people hover to find things.  
Some designers assume that primary actions should be visible and secondary ones revealed on hover. But this isn’t accessible—users who rely on assistive tech can’t access hidden elements.  

Instead:  
- Reveal secondary items as menus, without requiring a hover.  
- Lower the contrast of secondary icons and darken them on hover.  
- Never make people hover just to find essential content.

---

The author shared a powerful reminder at the end of the article:  
> Remember that we aren’t designing for designers. We are designing for a diverse set of users with different needs and varying technologies for accessing computers.

---

[Read the full article here](https://medium.com/salesforce-ux/7-things-every-designer-needs-to-know-about-accessibility-64f105f0881b)
