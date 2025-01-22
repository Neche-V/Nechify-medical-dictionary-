# Nechify: Simple Medical Dictionary App

# Dictionary containing 50 anatomy-related words and their meanings
medical_dictionary = {
    "Heart": "A muscular organ that pumps blood through the circulatory system.",
    "Lungs": "Organs that facilitate the exchange of oxygen and carbon dioxide.",
    "Brain": "The control center of the body, responsible for thought and coordination.",
    "Liver": "An organ that detoxifies chemicals and metabolizes drugs.",
    "Kidney": "A pair of organs that filter blood and produce urine.",
    "Stomach": "An organ that breaks down food using digestive acids.",
    "Skin": "The body's largest organ, protecting against external elements.",
    "Skeleton": "A framework of bones supporting the body structure.",
    "Muscle": "Tissues that contract to produce movement in the body.",
    "Nerves": "Fibers that transmit signals between different parts of the body.",
    "Esophagus": "A tube that connects the throat to the stomach.",
    "Pancreas": "An organ that produces insulin and digestive enzymes.",
    "Gallbladder": "Stores bile produced by the liver for digestion.",
    "Small Intestine": "An organ that absorbs nutrients from digested food.",
    "Large Intestine": "Absorbs water and forms solid waste (feces).",
    "Bladder": "An organ that stores urine before excretion.",
    "Spinal Cord": "A bundle of nerves transmitting signals between brain and body.",
    "Veins": "Blood vessels that carry blood back to the heart.",
    "Arteries": "Blood vessels that carry oxygen-rich blood from the heart.",
    "Capillaries": "Tiny blood vessels that connect arteries and veins.",
    "Tendon": "A tissue connecting muscle to bone.",
    "Ligament": "A tissue connecting bones to each other at joints.",
    "Cartilage": "A flexible connective tissue in joints and other structures.",
    "Diaphragm": "A muscle that aids in breathing by moving up and down.",
    "Thyroid": "A gland that regulates metabolism and energy levels.",
    "Lymph Nodes": "Small glands that filter lymph fluid and fight infection.",
    "Spleen": "An organ that filters blood and helps fight infections.",
    "Appendix": "A small tube attached to the large intestine with no essential function.",
    "Ureter": "A tube that carries urine from kidney to bladder.",
    "Urethra": "A tube that allows urine to exit the body.",
    "Femur": "The thigh bone, the longest bone in the human body.",
    "Humerus": "The upper arm bone connecting shoulder and elbow.",
    "Patella": "Commonly known as the kneecap, protects the knee joint.",
    "Cranium": "The skull bone that protects the brain.",
    "Ribs": "Bones that protect the chest cavity and organs within.",
    "Pelvis": "The lower part of the torso, supports abdominal organs.",
    "Bronchi": "Airways that lead from the trachea to the lungs.",
    "Trachea": "The windpipe, carrying air to and from the lungs.",
    "Cornea": "The transparent front part of the eye.",
    "Retina": "The inner layer of the eye that detects light.",
    "Aorta": "The largest artery in the body carrying blood from the heart.",
    "Alveoli": "Tiny air sacs in the lungs for gas exchange.",
    "Phalanges": "Bones of the fingers and toes.",
    "Scapula": "The shoulder blade bone.",
    "Clavicle": "The collarbone, connecting the arm to the body.",
    "Mandible": "The lower jawbone, used for chewing.",
    "Maxilla": "The upper jawbone, forming part of the face.",
    "Metacarpals": "Bones in the hand between wrist and fingers.",
    "Tarsals": "Bones in the foot forming the ankle region.",
    "Epidermis": "The outermost layer of skin."
}

# Function to search for a word in the medical dictionary
def search_medical_term(term):
    term = term.capitalize()
    if term in medical_dictionary:
        print(f"{term}: {medical_dictionary[term]}")
    else:
        print("Sorry, the term is not found in the dictionary.")

# Main program loop
if __name__ == "__main__":
    print("Welcome to Nechify - Medical Dictionary")
    while True:
        user_input = input("\nEnter an anatomy term to look up (or 'exit' to quit): ").strip()
        if user_input.lower() == 'exit':
            print("Thank you for using Nechify!")
            break
        search_medical_term(user_input)
