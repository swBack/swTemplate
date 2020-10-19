# swTemplate
# Shadow Cell
<code>
            
            containerView?.layer.cornerRadius = 10
            containerView?.layer.shadowOpacity = 1
            containerView?.layer.shadowRadius = 2
            containerView?.layer.shadowColor = UIColor.black.cgColor
            containerView?.layer.shadowOffset = CGSize(width: 3, height: 3)
            containerView?.backgroundColor = UIColor.clear
</code>

<code>
            
            clipView?.layer.cornerRadius = 10
            clipView?.backgroundColor = UIColor.white
            clipView?.layer.masksToBounds = true
</code>

#BottomRoundView
<code>
            
        let bezier = UIBezierPath(roundedRect: self.bounds,
                                  byRoundingCorners: [.bottomRight, .bottomLeft],
                     cornerRadii: CGSize(width: 50.0, height: 50.0))
        let maskLayer = CAShapeLayer()
        maskLayer.frame = self.bounds
        maskLayer.path  = bezier.cgPath
        self.layer.mask = maskLayer
</code>

#TEST Commit
##FIX CODE
